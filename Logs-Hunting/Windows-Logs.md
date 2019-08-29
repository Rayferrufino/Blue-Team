# Windows Logs
```bash
2019-08-05 16:42:33 ALLOW UDP 192.168.56.7 224.0.0.251 5353 5353 0 - - - - - - - SEND
2019-08-05 16:42:33 ALLOW UDP 192.168.56.7 192.168.56.255 137 137 0 - - - - - - - SEND
2019-08-05 16:42:39 ALLOW ICMP 192.168.56.7 192.168.56.2 - - 0 - - - - 8 0 - SEND
2019-08-05 16:42:40 ALLOW ICMP 192.168.56.7 192.168.56.2 - - 0 - - - - 8 0 - SEND
2019-08-05 16:42:41 ALLOW ICMP 192.168.56.7 192.168.56.2 - - 0 - - - - 8 0 - SEND
2019-08-05 16:42:42 ALLOW ICMP 192.168.56.7 192.168.56.2 - - 0 - - - - 8 0 - SEND
2019-08-05 16:42:47 DROP ICMP 192.168.56.3 192.168.56.7 - - 84 - - - - 8 0 - RECEIVE
2019-08-05 16:42:48 DROP ICMP 192.168.56.3 192.168.56.7 - - 84 - - - - 8 0 - RECEIVE
2019-08-05 16:42:49 DROP ICMP 192.168.56.3 192.168.56.7 - - 84 - - - - 8 0 - RECEIVE
2019-08-05 16:42:50 DROP ICMP 192.168.56.3 192.168.56.7 - - 84 - - - - 8 0 - RECEIVE
2019-08-05 16:42:51 DROP ICMP 192.168.56.3 192.168.56.7 - - 84 - - - - 8 0 - RECEIVE
2019-08-05 16:42:52 DROP ICMP 192.168.56.3 192.168.56.7 - - 84 - - - - 8 0 - RECEIVE
2019-08-05 16:43:01 ALLOW ICMP ::1 ff02::16 - - 0 - - - - 143 0 - SEND
2019-08-05 16:43:01 ALLOW 2 127.0.0.1 224.0.0.22 - - 0 - - - - - - - SEND
2019-08-05 16:43:01 ALLOW UDP 127.0.0.1 239.255.255.250 63778 1900 0 - - - - - - - SEND
2019-08-05 16:43:01 ALLOW UDP 127.0.0.1 239.255.255.250 63778 1900 0 - - - - - - - RECEIVE
2019-08-05 16:43:16 ALLOW ICMP 192.168.56.7 192.168.56.3 - - 0 - - - - 8 0 - SEND
2019-08-05 16:43:17 ALLOW ICMP 192.168.56.7 192.168.56.3 - - 0 - - - - 8 0 - SEND
2019-08-05 16:43:18 ALLOW ICMP 192.168.56.7 192.168.56.3 - - 0 - - - - 8 0 - SEND
2019-08-05 16:43:19 ALLOW ICMP 192.168.56.7 192.168.56.3 - - 0 - - - - 8 0 - SEND
``` 

# Windows Firewall Logs
## Version: 1.5
## Software: Microsoft Windows Firewall
## Time Format: Local
### Fields: date time action protocol src-ip dst-ip src-port dst-port size tcpflags tcpsyn tcpack tcpwin icmptype icmpcode info path

```bash

2019-08-23 20:14:47 ALLOW UDP 10.0.2.15 10.0.2.3 58453 53 0 - - - - - - - SEND
2019-08-23 20:14:47 ALLOW UDP 10.0.2.15 10.0.2.3 57128 53 0 - - - - - - - SEND
2019-08-23 20:14:47 ALLOW UDP 10.0.2.15 10.0.2.3 50730 53 0 - - - - - - - SEND
2019-08-23 20:14:47 ALLOW TCP 10.0.2.15 99.84.127.73 52585 443 0 - 0 0 0 - - - SEND
2019-08-23 20:14:47 ALLOW UDP 192.168.56.105 192.168.56.101 50730 53 0 - - - - - - - SEND
2019-08-23 20:14:50 ALLOW TCP 192.168.56.105 192.168.56.102 52586 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:15:23 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:24 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:25 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:26 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:27 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:28 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:29 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:30 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:31 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:32 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:33 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:34 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:35 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:36 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:37 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:38 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:39 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:40 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:41 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:42 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:43 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:44 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:45 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:46 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:48 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:49 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:15:50 DROP ICMP 192.168.56.102 192.168.56.105 - - 84 - - - - 8 0 - RECEIVE
2019-08-23 20:16:01 ALLOW TCP 192.168.56.105 192.168.56.102 52587 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:16:37 ALLOW TCP 192.168.56.105 192.168.56.102 52588 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:17:18 ALLOW UDP 10.0.2.15 10.0.2.3 49498 53 0 - - - - - - - SEND
2019-08-23 20:17:18 ALLOW TCP 10.0.2.15 52.230.222.68 52589 443 0 - 0 0 0 - - - SEND
2019-08-23 20:17:59 ALLOW TCP 192.168.56.105 192.168.56.102 52590 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:18:42 ALLOW UDP 0.0.0.0 255.255.255.255 68 67 0 - - - - - - - SEND
2019-08-23 20:18:42 ALLOW UDP 0.0.0.0 255.255.255.255 68 67 0 - - - - - - - RECEIVE
2019-08-23 20:19:00 ALLOW UDP 192.168.56.105 192.168.56.100 68 67 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW ICMP fe80::c0e8:35a9:ce52:5e05 ff02::16 - - 0 - - - - 143 0 - SEND
2019-08-23 20:19:00 ALLOW ICMP fe80::64a2:32fe:f749:b6ad ff02::16 - - 0 - - - - 143 0 - SEND
2019-08-23 20:19:00 ALLOW 2 10.0.2.15 224.0.0.22 - - 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW 2 192.168.56.105 224.0.0.22 - - 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW 2 169.254.94.5 224.0.0.22 - - 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW UDP 10.0.2.15 224.0.0.251 5353 5353 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW UDP 192.168.56.105 224.0.0.251 5353 5353 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW UDP 169.254.94.5 224.0.0.251 5353 5353 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW UDP 169.254.94.5 224.0.0.251 5353 5353 0 - - - - - - - RECEIVE
2019-08-23 20:19:00 ALLOW UDP fe80::64a2:32fe:f749:b6ad ff02::fb 5353 5353 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW UDP fe80::c0e8:35a9:ce52:5e05 ff02::fb 5353 5353 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW UDP fe80::64a2:32fe:f749:b6ad ff02::1:3 51643 5355 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW UDP 10.0.2.15 224.0.0.252 51643 5355 0 - - - - - - - SEND
2019-08-23 20:19:00 ALLOW UDP 192.168.56.105 224.0.0.252 51643 5355 0 - - - - - - - SEND
2019-08-23 20:19:15 ALLOW TCP 192.168.56.105 192.168.56.102 52591 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:19:36 ALLOW UDP 10.0.2.15 10.0.2.3 63487 53 0 - - - - - - - SEND
2019-08-23 20:19:36 ALLOW UDP 10.0.2.15 10.0.2.3 63204 53 0 - - - - - - - SEND
2019-08-23 20:19:36 ALLOW UDP 10.0.2.15 10.0.2.3 53030 53 0 - - - - - - - SEND
2019-08-23 20:19:36 ALLOW UDP 192.168.56.105 192.168.56.101 53030 53 0 - - - - - - - SEND
2019-08-23 20:19:36 ALLOW TCP 10.0.2.15 23.43.57.123 52592 443 0 - 0 0 0 - - - SEND
2019-08-23 20:19:48 ALLOW UDP 10.0.2.15 10.0.2.3 60447 53 0 - - - - - - - SEND
2019-08-23 20:19:48 ALLOW UDP 10.0.2.15 10.0.2.3 55124 53 0 - - - - - - - SEND
2019-08-23 20:19:48 ALLOW UDP 10.0.2.15 10.0.2.3 60968 53 0 - - - - - - - SEND
2019-08-23 20:19:48 ALLOW UDP 192.168.56.105 192.168.56.101 60968 53 0 - - - - - - - SEND
2019-08-23 20:19:48 ALLOW TCP 10.0.2.15 99.84.127.73 52593 443 0 - 0 0 0 - - - SEND
2019-08-23 20:20:01 ALLOW UDP 10.0.2.15 10.0.2.3 50815 53 0 - - - - - - - SEND
2019-08-23 20:20:05 ALLOW UDP 10.0.2.15 10.0.2.3 50119 53 0 - - - - - - - SEND
2019-08-23 20:20:39 ALLOW TCP 192.168.56.105 192.168.56.102 52594 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:21:34 ALLOW UDP fe80::c0e8:35a9:ce52:5e05 ff02::1:2 546 547 0 - - - - - - - SEND
2019-08-23 20:21:47 ALLOW TCP 192.168.56.105 192.168.56.102 52595 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:22:22 ALLOW TCP 192.168.56.105 192.168.56.102 52596 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:23:33 ALLOW TCP 192.168.56.105 192.168.56.102 52597 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:24:37 ALLOW UDP 10.0.2.15 10.0.2.3 59014 53 0 - - - - - - - SEND
2019-08-23 20:24:37 ALLOW UDP 10.0.2.15 10.0.2.3 57924 53 0 - - - - - - - SEND
2019-08-23 20:24:37 ALLOW UDP 10.0.2.15 10.0.2.3 55325 53 0 - - - - - - - SEND
2019-08-23 20:24:37 ALLOW UDP 192.168.56.105 192.168.56.101 55325 53 0 - - - - - - - SEND
2019-08-23 20:24:37 ALLOW TCP 10.0.2.15 23.43.57.123 52598 443 0 - 0 0 0 - - - SEND
2019-08-23 20:24:49 ALLOW UDP 10.0.2.15 10.0.2.3 53799 53 0 - - - - - - - SEND
2019-08-23 20:24:49 ALLOW UDP 10.0.2.15 10.0.2.3 52561 53 0 - - - - - - - SEND
2019-08-23 20:24:49 ALLOW UDP 10.0.2.15 10.0.2.3 55718 53 0 - - - - - - - SEND
2019-08-23 20:24:49 ALLOW TCP 10.0.2.15 99.84.127.73 52599 443 0 - 0 0 0 - - - SEND
2019-08-23 20:24:49 ALLOW UDP 192.168.56.105 192.168.56.101 55718 53 0 - - - - - - - SEND
2019-08-23 20:24:53 ALLOW TCP 192.168.56.105 192.168.56.102 52600 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:25:43 ALLOW UDP 0.0.0.0 255.255.255.255 68 67 0 - - - - - - - SEND
2019-08-23 20:25:43 ALLOW UDP 0.0.0.0 255.255.255.255 68 67 0 - - - - - - - RECEIVE
2019-08-23 20:26:04 ALLOW TCP 192.168.56.105 192.168.56.102 52601 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:26:35 ALLOW TCP 192.168.56.105 192.168.56.102 52602 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:27:47 ALLOW TCP 192.168.56.105 192.168.56.102 52603 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:28:41 ALLOW UDP fe80::c0e8:35a9:ce52:5e05 ff02::1:2 546 547 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP 192.168.56.105 192.168.56.100 68 67 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW ICMP fe80::64a2:32fe:f749:b6ad ff02::16 - - 0 - - - - 143 0 - SEND
2019-08-23 20:29:01 ALLOW ICMP fe80::c0e8:35a9:ce52:5e05 ff02::16 - - 0 - - - - 143 0 - SEND
2019-08-23 20:29:01 ALLOW 2 10.0.2.15 224.0.0.22 - - 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW 2 192.168.56.105 224.0.0.22 - - 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW 2 169.254.94.5 224.0.0.22 - - 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP 10.0.2.15 224.0.0.251 5353 5353 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP 192.168.56.105 224.0.0.251 5353 5353 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP 169.254.94.5 224.0.0.251 5353 5353 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP fe80::64a2:32fe:f749:b6ad ff02::fb 5353 5353 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP fe80::c0e8:35a9:ce52:5e05 ff02::fb 5353 5353 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP fe80::64a2:32fe:f749:b6ad ff02::1:3 58863 5355 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP 10.0.2.15 224.0.0.252 58863 5355 0 - - - - - - - SEND
2019-08-23 20:29:01 ALLOW UDP 192.168.56.105 224.0.0.252 58863 5355 0 - - - - - - - SEND
2019-08-23 20:29:11 ALLOW TCP 192.168.56.105 192.168.56.102 52604 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:29:37 ALLOW UDP 10.0.2.15 10.0.2.3 54765 53 0 - - - - - - - SEND
2019-08-23 20:29:37 ALLOW UDP 10.0.2.15 10.0.2.3 53160 53 0 - - - - - - - SEND
2019-08-23 20:29:37 ALLOW UDP 10.0.2.15 10.0.2.3 49635 53 0 - - - - - - - SEND
2019-08-23 20:29:37 ALLOW TCP 10.0.2.15 23.43.57.123 52605 443 0 - 0 0 0 - - - SEND
2019-08-23 20:29:37 ALLOW UDP 192.168.56.105 192.168.56.101 49635 53 0 - - - - - - - SEND
2019-08-23 20:29:50 ALLOW UDP 10.0.2.15 10.0.2.3 54150 53 0 - - - - - - - SEND
2019-08-23 20:29:50 ALLOW UDP 10.0.2.15 10.0.2.3 54952 53 0 - - - - - - - SEND
2019-08-23 20:29:50 ALLOW UDP 10.0.2.15 10.0.2.3 53518 53 0 - - - - - - - SEND
2019-08-23 20:29:50 ALLOW TCP 10.0.2.15 143.204.142.38 52606 443 0 - 0 0 0 - - - SEND
2019-08-23 20:29:50 ALLOW UDP 192.168.56.105 192.168.56.101 53518 53 0 - - - - - - - SEND
2019-08-23 20:29:58 ALLOW TCP 192.168.56.105 192.168.56.102 52607 55555 0 - 0 0 0 - - - SEND
2019-08-23 20:30:01 ALLOW UDP 10.0.2.15 10.0.2.3 55435 53 0 - - - - - - - SEND
```
# Windows Event Viewer Logs
## successful login attempt generated with Event Viewer
![Eventviewer](https://learndotresources.s3.amazonaws.com/workshop/5d42f98c2d669d000414097d/g02.png)

```bash


Log Name:      Security
Source:        Microsoft-Windows-Security-Auditing
Date:          8/23/2019 7:03:46 PM
Event ID:      4624
Task Category: Logon
Level:         Information
Keywords:      Audit Success
User:          N/A
Computer:      DESKTOP-PE6GMIK
Description:
An account was successfully logged on.

Subject:
    Security ID:        SYSTEM
    Account Name:        DESKTOP-PE6GMIK$
    Account Domain:        WORKGROUP
    Logon ID:        0x3E7

Logon Information:
    Logon Type:        5
    Restricted Admin Mode:    -
    Virtual Account:        No
    Elevated Token:        Yes

Impersonation Level:        Impersonation

New Logon:
    Security ID:        SYSTEM
    Account Name:        SYSTEM
    Account Domain:        NT AUTHORITY
    Logon ID:        0x3E7
    Linked Logon ID:        0x0
    Network Account Name:    -
    Network Account Domain:    -
    Logon GUID:        {00000000-0000-0000-0000-000000000000}

Process Information:
    Process ID:        0x248
    Process Name:        C:\Windows\System32\services.exe

Network Information:
    Workstation Name:    -
    Source Network Address:    -
    Source Port:        -

Detailed Authentication Information:
    Logon Process:        Advapi  
    Authentication Package:    Negotiate
    Transited Services:    -
    Package Name (NTLM only):    -
    Key Length:        0

This event is generated when a logon session is created. It is generated on the computer that was accessed.

The subject fields indicate the account on the local system which requested the logon. This is most commonly a service such as the Server service, or a local process such as Winlogon.exe or Services.exe.

The logon type field indicates the kind of logon that occurred. The most common types are 2 (interactive) and 3 (network).

The New Logon fields indicate the account for whom the new logon was created, i.e. the account that was logged on.

The network fields indicate where a remote logon request originated. Workstation name is not always available and may be left blank in some cases.

The impersonation level field indicates the extent to which a process in the logon session can impersonate.

The authentication information fields provide detailed information about this specific logon request.
    - Logon GUID is a unique identifier that can be used to correlate this event with a KDC event.
    - Transited services indicate which intermediate services have participated in this logon request.
    - Package name indicates which sub-protocol was used among the NTLM protocols.
    - Key length indicates the length of the generated session key. This will be 0 if no session key was requested.
Event Xml:
<Event xmlns="http://schemas.microsoft.com/win/2004/08/events/event">
  <System>
    <Provider Name="Microsoft-Windows-Security-Auditing" Guid="{54849625-5478-4994-a5ba-3e3b0328c30d}" />
    <EventID>4624</EventID>
    <Version>2</Version>
    <Level>0</Level>
    <Task>12544</Task>
    <Opcode>0</Opcode>
    <Keywords>0x8020000000000000</Keywords>
    <TimeCreated SystemTime="2019-08-23T23:03:46.014232000Z" />
    <EventRecordID>9400</EventRecordID>
    <Correlation ActivityID="{87674bbe-59f5-0000-334c-6787f559d501}" />
    <Execution ProcessID="612" ThreadID="5720" />
    <Channel>Security</Channel>
    <Computer>DESKTOP-PE6GMIK</Computer>
    <Security />
  </System>
  <EventData>
    <Data Name="SubjectUserSid">S-1-5-18</Data>
    <Data Name="SubjectUserName">DESKTOP-PE6GMIK$</Data>
    <Data Name="SubjectDomainName">WORKGROUP</Data>
    <Data Name="SubjectLogonId">0x3e7</Data>
    <Data Name="TargetUserSid">S-1-5-18</Data>
    <Data Name="TargetUserName">SYSTEM</Data>
    <Data Name="TargetDomainName">NT AUTHORITY</Data>
    <Data Name="TargetLogonId">0x3e7</Data>
    <Data Name="LogonType">5</Data>
    <Data Name="LogonProcessName">Advapi  </Data>
    <Data Name="AuthenticationPackageName">Negotiate</Data>
    <Data Name="WorkstationName">-</Data>
    <Data Name="LogonGuid">{00000000-0000-0000-0000-000000000000}</Data>
    <Data Name="TransmittedServices">-</Data>
    <Data Name="LmPackageName">-</Data>
    <Data Name="KeyLength">0</Data>
    <Data Name="ProcessId">0x248</Data>
    <Data Name="ProcessName">C:\Windows\System32\services.exe</Data>
    <Data Name="IpAddress">-</Data>
    <Data Name="IpPort">-</Data>
    <Data Name="ImpersonationLevel">%%1833</Data>
    <Data Name="RestrictedAdminMode">-</Data>
    <Data Name="TargetOutboundUserName">-</Data>
    <Data Name="TargetOutboundDomainName">-</Data>
    <Data Name="VirtualAccount">%%1843</Data>
    <Data Name="TargetLinkedLogonId">0x0</Data>
    <Data Name="ElevatedToken">%%1842</Data>
  </EventData>
</Event>
```
