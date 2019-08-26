# Warm-up Exercise

### Use wireshark to identify what types of behavior are happening in each of the following pcap samples
### There are at least 3 different actions.

![Wireshark](https://kmqokw.dm.files.1drv.com/y4mKnvHgHA1zOWtQ3c9nOx1u33j45z0dSRcjMwO14An51Eo4q3s-MQ5FdUDvLR-J2JE8m4gWyQYLgjlTsCXsjrOBmLWJ72WVyif_IZXSgy4n5p1GpkZuBaZWDbhH4yIJnBHtIybdXuiEooa4IDmWgu3mxJAQf_mWmhOTUmmtxjPIEMp1JL2DFsaCsZjRdOKYFmsyPFWWmjczVcW-H581HWH0g?width=1365&height=613&cropmode=none)
![Wireshark](https://k8qokw.dm.files.1drv.com/y4m7Mex9yyhAF8jHB_35vTFa04ZfOMj3sRjlDr6kZeu4R827MibuSxmia22jWtZ2czKChkLtQiAvclsUWzRo5tqSjNjVGqhbyyRQs_q67j330jx88nbyqCyDb6JWMfLP2CzpzYfHoqU5tkuTgX3cdqUBvkwQ2-VIlR5gNNEDHpVpxijs20gDAxvwDvG3tOyduxRtmIKcvmsSG-w6UN6E2GGfQ?width=983&height=640&cropmode=none)
![Wireshark](https://vgbbeg.dm.files.1drv.com/y4mlWtgcZwGYTbcA_6JSYQyjFCbUbIdS8AxphKGiT1EYs0pv-moh10npFz4RKCX-kc0IMiymS3RT2ADgjvo6mU-ous3uJdy-4vg_q6TrQ1rCvu-4F8vxGr8rBPQFxh-soEqIMvl5jBsJ7gUQ8kPYjvHaqY3m2HPC4bVPa8Zpo7pBwVtxt7t7vSpFQYdC8ntI2fnhk8NliCnn2JWnCDP7ULivg?width=814&height=604&cropmode=none)
![wireshark traffic](https://umbbeg.dm.files.1drv.com/y4mIwOdKe7HmfhTDVl1OxrwGCpQfX3tEhYZmcEGoJLT0DjA0WAG-ayWcCp4Esc1F7_n4IRS_v5aZtzCfi_y2tUcI38qpeZH86jxzXXkyYMR8jRQKMP91ojrvBX17N1x2IHfc4_yTs-EAssuJGR2V-57SuCmhxjW8n1IdkTizx4NAgnKHkuaoKaJLJEQoxC2SXEA6t8lPEuGEbSqX7DWele-Jg?width=763&height=502&cropmode=none)

# Run Snort with the capture
1. Create an empty rules file named fullstack.rules, and an empty directory named logs
2. Run snort -l ./logs -c fullstack.rules -r captured.pcap
3. Snort should exit cleanly. There may be warnings, but no errors should occur

# Alerting on scans
```bash
root@kali:/media/sf_Downloads# snort -l ./logs -c fullstack.rules -r Metasploit-traffic.pcap 
Running in IDS mode

        --== Initializing Snort ==--
Initializing Output Plugins!
Initializing Preprocessors!
Initializing Plug-ins!
Parsing Rules file "fullstack.rules"
Tagged Packet Limit: 256
Log directory = ./logs

+++++++++++++++++++++++++++++++++++++++++++++++++++
Initializing rule chains...
1 Snort rules read
    1 detection rules
    0 decoder rules
    0 preprocessor rules
1 Option Chains linked into 1 Chain Headers
0 Dynamic rules
+++++++++++++++++++++++++++++++++++++++++++++++++++

+-------------------[Rule Port Counts]---------------------------------------
|             tcp     udp    icmp      ip
|     src       0       0       0       0
|     dst       0       0       0       0
|     any       0       0       1       0
|      nc       0       0       1       0
|     s+d       0       0       0       0
+----------------------------------------------------------------------------

+-----------------------[detection-filter-config]------------------------------
| memory-cap : 1048576 bytes
+-----------------------[detection-filter-rules]-------------------------------
| none
-------------------------------------------------------------------------------

+-----------------------[rate-filter-config]-----------------------------------
| memory-cap : 1048576 bytes
+-----------------------[rate-filter-rules]------------------------------------
| none
-------------------------------------------------------------------------------

+-----------------------[event-filter-config]----------------------------------
| memory-cap : 1048576 bytes
+-----------------------[event-filter-global]----------------------------------
+-----------------------[event-filter-local]-----------------------------------
| none
+-----------------------[suppression]------------------------------------------
| none
-------------------------------------------------------------------------------
Rule application order: activation->dynamic->pass->drop->sdrop->reject->alert->log
Verifying Preprocessor Configurations!

[ Port Based Pattern Matching Memory ]
pcap DAQ configured to read-file.
Acquiring network traffic from "Metasploit-traffic.pcap".
Reload thread starting...
Reload thread started, thread 0x7ff0ae738700 (2980)

        --== Initialization Complete ==--

   ,,_     -*> Snort! <*-
  o"  )~   Version 2.9.7.0 GRE (Build 149) 
   ''''    By Martin Roesch & The Snort Team: http://www.snort.org/contact#team
           Copyright (C) 2014 Cisco and/or its affiliates. All rights reserved.
           Copyright (C) 1998-2013 Sourcefire, Inc., et al.
           Using libpcap version 1.8.1
           Using PCRE version: 8.39 2016-06-14
           Using ZLIB version: 1.2.11
===============================================================================
Run time for packet processing was 1.1664 seconds
Snort processed 2282 packets.
Snort ran for 0 days 0 hours 0 minutes 1 seconds
   Pkts/sec:         2282
===============================================================================
Memory usage summary:
  Total non-mmapped bytes (arena):       2260992
  Bytes in mapped regions (hblkhd):      17117184
  Total allocated space (uordblks):      2066976
  Total free space (fordblks):           194016
  Topmost releasable block (keepcost):   40128
===============================================================================
Packet I/O Totals:
   Received:         2282
   Analyzed:         2282 (100.000%)
    Dropped:            0 (  0.000%)
   Filtered:            0 (  0.000%)
Outstanding:            0 (  0.000%)
   Injected:            0
===============================================================================
Breakdown by protocol (includes rebuilt packets):
        Eth:         2282 (100.000%)
       VLAN:            0 (  0.000%)
        IP4:         2222 ( 97.371%)
       Frag:            0 (  0.000%)
       ICMP:           16 (  0.701%)
        UDP:           38 (  1.665%)
        TCP:         2133 ( 93.471%)
        IP6:           49 (  2.147%)
    IP6 Ext:           84 (  3.681%)
   IP6 Opts:           35 (  1.534%)
      Frag6:            0 (  0.000%)
      ICMP6:           35 (  1.534%)
       UDP6:           14 (  0.613%)
       TCP6:            0 (  0.000%)
     Teredo:            0 (  0.000%)
    ICMP-IP:            0 (  0.000%)
    IP4/IP4:            0 (  0.000%)
    IP4/IP6:            0 (  0.000%)
    IP6/IP4:            0 (  0.000%)
    IP6/IP6:            0 (  0.000%)
        GRE:            0 (  0.000%)
    GRE Eth:            0 (  0.000%)
   GRE VLAN:            0 (  0.000%)
    GRE IP4:            0 (  0.000%)
    GRE IP6:            0 (  0.000%)
GRE IP6 Ext:            0 (  0.000%)
   GRE PPTP:            0 (  0.000%)
    GRE ARP:            0 (  0.000%)
    GRE IPX:            0 (  0.000%)
   GRE Loop:            0 (  0.000%)
       MPLS:            0 (  0.000%)
        ARP:           11 (  0.482%)
        IPX:            0 (  0.000%)
   Eth Loop:            0 (  0.000%)
   Eth Disc:            0 (  0.000%)
   IP4 Disc:            0 (  0.000%)
   IP6 Disc:            0 (  0.000%)
   TCP Disc:            0 (  0.000%)
   UDP Disc:            0 (  0.000%)
  ICMP Disc:            0 (  0.000%)
All Discard:            0 (  0.000%)
      Other:           35 (  1.534%)
Bad Chk Sum:           66 (  2.892%)
    Bad TTL:            0 (  0.000%)
     S5 G 1:            0 (  0.000%)
     S5 G 2:            0 (  0.000%)
      Total:         2282
===============================================================================
Action Stats:
     Alerts:           51 (  2.235%)
     Logged:           51 (  2.235%)
     Passed:            0 (  0.000%)
Limits:
      Match:            0
      Queue:            0
        Log:            0
      Event:            0
      Alert:            0
Verdicts:
      Allow:         2282 (100.000%)
      Block:            0 (  0.000%)
    Replace:            0 (  0.000%)
  Whitelist:            0 (  0.000%)
  Blacklist:            0 (  0.000%)
     Ignore:            0 (  0.000%)
      Retry:            0 (  0.000%)
===============================================================================
Snort exiting
```
