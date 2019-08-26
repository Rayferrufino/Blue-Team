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
