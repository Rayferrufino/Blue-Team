# normal DNS requests made via remote client
```bash
Aug 25 20:25:46 dnsmasq[2890]: reply e16973.a.akamaiedge.net is 23.221.48.119
Aug 25 20:25:56 dnsmasq[2890]: query[A] null-byte.com from 192.168.56.102
Aug 25 20:25:56 dnsmasq[2890]: forwarded null-byte.com to 1.0.0.1
Aug 25 20:25:56 dnsmasq[2890]: reply null-byte.com is 104.193.19.59
Aug 25 20:25:56 dnsmasq[2890]: query[AAAA] null-byte.com from 192.168.56.102
Aug 25 20:25:56 dnsmasq[2890]: forwarded null-byte.com to 1.0.0.1
Aug 25 20:25:56 dnsmasq[2890]: reply null-byte.com is NODATA-IPv6
Aug 25 20:26:00 dnsmasq[2890]: query[PTR] 102.56.168.192.in-addr.arpa from 127.0.0.1
Aug 25 20:26:00 dnsmasq[2890]: forwarded 102.56.168.192.in-addr.arpa to 1.0.0.1
Aug 25 20:26:00 dnsmasq[2890]: reply 192.168.56.102 is NXDOMAIN
Aug 25 20:26:34 dnsmasq[2890]: query[A] detectportal.firefox.com from 127.0.0.1
Aug 25 20:26:34 dnsmasq[2890]: forwarded detectportal.firefox.com to 1.0.0.1
Aug 25 20:26:34 dnsmasq[2890]: query[AAAA] detectportal.firefox.com from 127.0.0.1
Aug 25 20:26:34 dnsmasq[2890]: forwarded detectportal.firefox.com to 1.0.0.1
Aug 25 20:26:34 dnsmasq[2890]: reply detectportal.firefox.com is <CNAME>
Aug 25 20:26:34 dnsmasq[2890]: reply detectportal.prod.mozaws.net is <CNAME>
Aug 25 20:26:34 dnsmasq[2890]: reply detectportal.firefox.com-v2.edgesuite.net is <CNAME>
Aug 25 20:26:34 dnsmasq[2890]: reply a1089.dscd.akamai.net is 23.50.53.184
Aug 25 20:26:34 dnsmasq[2890]: reply a1089.dscd.akamai.net is 23.50.53.187
Aug 25 20:26:34 dnsmasq[2890]: reply detectportal.firefox.com is <CNAME>
Aug 25 20:26:34 dnsmasq[2890]: reply detectportal.prod.mozaws.net is <CNAME>
Aug 25 20:26:34 dnsmasq[2890]: reply detectportal.firefox.com-v2.edgesuite.net is <CNAME>
Aug 25 20:26:34 dnsmasq[2890]: reply a1089.dscd.akamai.net is 2600:141b:13::1732:35bb
Aug 25 20:26:34 dnsmasq[2890]: reply a1089.dscd.akamai.net is 2600:141b:13::1732:35b8
Aug 25 20:26:38 dnsmasq[2890]: query[A] safebrowsing.googleapis.com from 127.0.0.1
Aug 25 20:26:38 dnsmasq[2890]: forwarded safebrowsing.googleapis.com to 1.0.0.1
Aug 25 20:26:38 dnsmasq[2890]: query[AAAA] safebrowsing.googleapis.com from 127.0.0.1
Aug 25 20:26:38 dnsmasq[2890]: forwarded safebrowsing.googleapis.com to 1.0.0.1
Aug 25 20:26:38 dnsmasq[2890]: reply safebrowsing.googleapis.com is 172.217.10.106
Aug 25 20:26:38 dnsmasq[2890]: reply safebrowsing.googleapis.com is 2607:f8b0:4006:812::200a
Aug 25 20:26:38 dnsmasq[2890]: query[A] ocsp.pki.goog from 127.0.0.1
Aug 25 20:26:38 dnsmasq[2890]: forwarded ocsp.pki.goog to 1.0.0.1
Aug 25 20:26:38 dnsmasq[2890]: query[AAAA] ocsp.pki.goog from 127.0.0.1
Aug 25 20:26:38 dnsmasq[2890]: forwarded ocsp.pki.goog to 1.0.0.1
Aug 25 20:26:38 dnsmasq[2890]: reply ocsp.pki.goog is <CNAME>
Aug 25 20:26:38 dnsmasq[2890]: reply pki-goog.l.google.com is 172.217.10.131
Aug 25 20:26:38 dnsmasq[2890]: reply ocsp.pki.goog is <CNAME>
Aug 25 20:26:38 dnsmasq[2890]: reply pki-goog.l.google.com is 2607:f8b0:4006:818::2003
Aug 25 20:28:12 dnsmasq[2890]: query[A] img-getpocket.cdn.mozilla.net from 192.168.56.102
Aug 25 20:28:12 dnsmasq[2890]: forwarded img-getpocket.cdn.mozilla.net to 1.0.0.1
Aug 25 20:28:12 dnsmasq[2890]: query[AAAA] img-getpocket.cdn.mozilla.net from 192.168.56.102
Aug 25 20:28:12 dnsmasq[2890]: forwarded img-getpocket.cdn.mozilla.net to 1.0.0.1
Aug 25 20:28:12 dnsmasq[2890]: reply img-getpocket.cdn.mozilla.net is <CNAME>
Aug 25 20:28:12 dnsmasq[2890]: reply img-getpocket-cdn.prod.mozaws.net is <CNAME>
Aug 25 20:28:12 dnsmasq[2890]: reply img-getpocket.cdn.mozilla.net.edgekey.net is <CNAME>
Aug 25 20:28:12 dnsmasq[2890]: reply e8220.dscd.akamaiedge.net is 23.52.164.254
Aug 25 20:28:12 dnsmasq[2890]: reply img-getpocket.cdn.mozilla.net is <CNAME>
Aug 25 20:28:12 dnsmasq[2890]: reply img-getpocket-cdn.prod.mozaws.net is <CNAME>
Aug 25 20:28:12 dnsmasq[2890]: reply img-getpocket.cdn.mozilla.net.edgekey.net is <CNAME>
Aug 25 20:28:12 dnsmasq[2890]: reply e8220.dscd.akamaiedge.net is 2600:1400:d:58d::201c
Aug 25 20:28:12 dnsmasq[2890]: reply e8220.dscd.akamaiedge.net is 2600:1400:d:58e::201c
Aug 25 20:28:12 dnsmasq[2890]: reply e8220.dscd.akamaiedge.net is 2600:1400:d:58f::201c
Aug 25 20:28:12 dnsmasq[2890]: query[A] ocsp.digicert.com from 192.168.56.102
Aug 25 20:28:12 dnsmasq[2890]: cached ocsp.digicert.com is <CNAME>
Aug 25 20:28:12 dnsmasq[2890]: cached cs9.wac.phicdn.net is 72.21.91.29
Aug 25 20:28:12 dnsmasq[2890]: query[AAAA] ocsp.digicert.com from 192.168.56.102
Aug 25 20:28:12 dnsmasq[2890]: cached ocsp.digicert.com is <CNAME>
Aug 25 20:28:12 dnsmasq[2890]: cached cs9.wac.phicdn.net is NODATA-IPv6
Aug 25 20:28:21 dnsmasq[2890]: query[A] searx.me from 192.168.56.102
Aug 25 20:28:21 dnsmasq[2890]: forwarded searx.me to 1.0.0.1
Aug 25 20:28:21 dnsmasq[2890]: query[AAAA] searx.me from 192.168.56.102
Aug 25 20:28:21 dnsmasq[2890]: forwarded searx.me to 1.0.0.1
Aug 25 20:28:21 dnsmasq[2890]: reply searx.me is 194.150.168.104
Aug 25 20:28:21 dnsmasq[2890]: reply searx.me is NODATA-IPv6
Aug 25 20:28:21 dnsmasq[2890]: query[A] ocsp.int-x3.letsencrypt.org from 192.168.56.102
Aug 25 20:28:21 dnsmasq[2890]: forwarded ocsp.int-x3.letsencrypt.org to 1.0.0.1
Aug 25 20:28:21 dnsmasq[2890]: query[AAAA] ocsp.int-x3.letsencrypt.org from 192.168.56.102
Aug 25 20:28:21 dnsmasq[2890]: forwarded ocsp.int-x3.letsencrypt.org to 1.0.0.1
Aug 25 20:28:21 dnsmasq[2890]: reply ocsp.int-x3.letsencrypt.org is <CNAME>
Aug 25 20:28:21 dnsmasq[2890]: reply ocsp.int-x3.letsencrypt.org.edgesuite.net is <CNAME>
Aug 25 20:28:21 dnsmasq[2890]: reply a771.dscq.akamai.net is 23.50.53.179
Aug 25 20:28:21 dnsmasq[2890]: reply a771.dscq.akamai.net is 23.50.53.177
Aug 25 20:28:21 dnsmasq[2890]: reply ocsp.int-x3.letsencrypt.org is <CNAME>
Aug 25 20:28:21 dnsmasq[2890]: reply ocsp.int-x3.letsencrypt.org.edgesuite.net is <CNAME>
Aug 25 20:28:21 dnsmasq[2890]: reply a771.dscq.akamai.net is 2600:141b:13::17d7:8253
Aug 25 20:28:21 dnsmasq[2890]: reply a771.dscq.akamai.net is 2600:141b:13::17d7:8280
Aug 25 20:28:25 dnsmasq[2890]: query[A] getpocket.cdn.mozilla.net from 192.168.56.102
Aug 25 20:28:25 dnsmasq[2890]: forwarded getpocket.cdn.mozilla.net to 1.0.0.1
Aug 25 20:28:25 dnsmasq[2890]: query[AAAA] getpocket.cdn.mozilla.net from 192.168.56.102
Aug 25 20:28:25 dnsmasq[2890]: forwarded getpocket.cdn.mozilla.net to 1.0.0.1
Aug 25 20:28:25 dnsmasq[2890]: reply getpocket.cdn.mozilla.net is <CNAME>
Aug 25 20:28:25 dnsmasq[2890]: reply getpocket-cdn.prod.mozaws.net is <CNAME>
Aug 25 20:28:25 dnsmasq[2890]: reply getpocket.cdn.mozilla.net.edgekey.net is <CNAME>
Aug 25 20:28:25 dnsmasq[2890]: reply e8220.dscd.akamaiedge.net is 23.52.164.254
Aug 25 20:28:25 dnsmasq[2890]: reply getpocket.cdn.mozilla.net is <CNAME>
Aug 25 20:28:25 dnsmasq[2890]: reply getpocket-cdn.prod.mozaws.net is <CNAME>
Aug 25 20:28:25 dnsmasq[2890]: reply getpocket.cdn.mozilla.net.edgekey.net is <CNAME>
Aug 25 20:28:25 dnsmasq[2890]: reply e8220.dscd.akamaiedge.net is 2600:1400:d:58e::201c
Aug 25 20:28:25 dnsmasq[2890]: reply e8220.dscd.akamaiedge.net is 2600:1400:d:58f::201c
Aug 25 20:28:25 dnsmasq[2890]: reply e8220.dscd.akamaiedge.net is 2600:1400:d:5a7::201c
Aug 25 20:28:26 dnsmasq[2890]: query[A] searx.me from 192.168.56.102
Aug 25 20:28:26 dnsmasq[2890]: cached searx.me is 194.150.168.104
Aug 25 20:28:26 dnsmasq[2890]: query[AAAA] searx.me from 192.168.56.102
Aug 25 20:28:26 dnsmasq[2890]: cached searx.me is NODATA-IPv6
Aug 25 20:28:26 dnsmasq[2890]: query[A] searx.me from 192.168.56.102
Aug 25 20:28:26 dnsmasq[2890]: cached searx.me is 194.150.168.104
Aug 25 20:28:26 dnsmasq[2890]: query[A] searx.me from 192.168.56.102
Aug 25 20:28:26 dnsmasq[2890]: cached searx.me is 194.150.168.104
Aug 25 20:28:45 dnsmasq[2890]: query[A] www.wikihow.com from 192.168.56.102
Aug 25 20:28:45 dnsmasq[2890]: forwarded www.wikihow.com to 1.0.0.1
Aug 25 20:28:45 dnsmasq[2890]: query[AAAA] www.wikihow.com from 192.168.56.102
Aug 25 20:28:45 dnsmasq[2890]: forwarded www.wikihow.com to 1.0.0.1
Aug 25 20:28:45 dnsmasq[2890]: reply www.wikihow.com is <CNAME>
Aug 25 20:28:45 dnsmasq[2890]: reply f4.shared.us-eu.fastly.net is 151.101.210.110
Aug 25 20:28:45 dnsmasq[2890]: reply www.wikihow.com is <CNAME>
Aug 25 20:28:45 dnsmasq[2890]: reply f4.shared.us-eu.fastly.net is NODATA-IPv6
Aug 25 20:28:47 dnsmasq[2890]: query[A] medium.com from 192.168.56.102
Aug 25 20:28:47 dnsmasq[2890]: forwarded medium.com to 1.0.0.1
Aug 25 20:28:47 dnsmasq[2890]: query[AAAA] medium.com from 192.168.56.102
Aug 25 20:28:47 dnsmasq[2890]: forwarded medium.com to 1.0.0.1
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 104.16.124.127
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 104.16.120.127
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 104.16.121.127
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 104.16.122.127
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 104.16.123.127
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 2606:4700::6810:7c7f
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 2606:4700::6810:787f
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 2606:4700::6810:797f
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 2606:4700::6810:7a7f
Aug 25 20:28:48 dnsmasq[2890]: reply medium.com is 2606:4700::6810:7b7f
Aug 25 20:28:50 dnsmasq[2890]: query[A] glyph.medium.com from 192.168.56.102
Aug 25 20:28:50 dnsmasq[2890]: forwarded glyph.medium.com to 1.0.0.1
Aug 25 20:28:50 dnsmasq[2890]: query[AAAA] glyph.medium.com from 192.168.56.102
Aug 25 20:28:50 dnsmasq[2890]: forwarded glyph.medium.com to 1.0.0.1
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 104.16.119.145
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 104.16.120.145
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 104.16.121.145
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 104.16.117.145
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 104.16.118.145
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 2606:4700::6810:7891
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 2606:4700::6810:7991
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 2606:4700::6810:7591
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 2606:4700::6810:7691
Aug 25 20:28:50 dnsmasq[2890]: reply glyph.medium.com is 2606:4700::6810:7791
Aug 25 20:28:50 dnsmasq[2890]: query[A] cdn-client.medium.com from 192.168.56.102
Aug 25 20:28:50 dnsmasq[2890]: forwarded cdn-client.medium.com to 1.0.0.1
Aug 25 20:28:50 dnsmasq[2890]: query[AAAA] cdn-client.medium.com from 192.168.56.102
Aug 25 20:28:50 dnsmasq[2890]: forwarded cdn-client.medium.com to 1.0.0.1
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 104.16.117.145
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 104.16.118.145
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 104.16.119.145
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 104.16.120.145
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 104.16.121.145
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 2606:4700::6810:7791
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 2606:4700::6810:7891
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 2606:4700::6810:7991
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 2606:4700::6810:7591
Aug 25 20:28:50 dnsmasq[2890]: reply cdn-client.medium.com is 2606:4700::6810:7691
Aug 25 20:28:50 dnsmasq[2890]: query[A] miro.medium.com from 192.168.56.102
Aug 25 20:28:50 dnsmasq[2890]: forwarded miro.medium.com to 1.0.0.1
Aug 25 20:28:50 dnsmasq[2890]: query[AAAA] miro.medium.com from 192.168.56.102
Aug 25 20:28:50 dnsmasq[2890]: forwarded miro.medium.com to 1.0.0.1
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 104.16.121.145
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 104.16.117.145
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 104.16.118.145
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 104.16.119.145
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 104.16.120.145
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 2606:4700::6810:7591
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 2606:4700::6810:7691
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 2606:4700::6810:7791
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 2606:4700::6810:7891
Aug 25 20:28:50 dnsmasq[2890]: reply miro.medium.com is 2606:4700::6810:7991
Aug 25 20:28:51 dnsmasq[2890]: query[A] cdn-images-1.medium.com from 192.168.56.102
Aug 25 20:28:51 dnsmasq[2890]: forwarded cdn-images-1.medium.com to 1.0.0.1
Aug 25 20:28:51 dnsmasq[2890]: query[AAAA] cdn-images-1.medium.com from 192.168.56.102
Aug 25 20:28:51 dnsmasq[2890]: forwarded cdn-images-1.medium.com to 1.0.0.1
Aug 25 20:28:51 dnsmasq[2890]: query[A] cdn-static-1.medium.com from 192.168.56.102
Aug 25 20:28:51 dnsmasq[2890]: forwarded cdn-static-1.medium.com to 1.0.0.1
Aug 25 20:28:51 dnsmasq[2890]: query[AAAA] cdn-static-1.medium.com from 192.168.56.102
Aug 25 20:28:51 dnsmasq[2890]: forwarded cdn-static-1.medium.com to 1.0.0.1
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 104.16.121.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 104.16.117.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 104.16.118.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 104.16.119.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 104.16.120.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 2606:4700::6810:7591
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 2606:4700::6810:7691
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 2606:4700::6810:7791
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 2606:4700::6810:7891
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-images-1.medium.com is 2606:4700::6810:7991
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 2606:4700::6810:7691
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 2606:4700::6810:7791
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 2606:4700::6810:7891
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 2606:4700::6810:7991
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 2606:4700::6810:7591
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 104.16.117.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 104.16.118.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 104.16.119.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 104.16.120.145
Aug 25 20:28:51 dnsmasq[2890]: reply cdn-static-1.medium.com is 104.16.121.145
Aug 25 20:28:52 dnsmasq[2890]: query[A] smartlock.google.com from 192.168.56.102
Aug 25 20:28:52 dnsmasq[2890]: forwarded smartlock.google.com to 1.0.0.1
Aug 25 20:28:52 dnsmasq[2890]: query[AAAA] smartlock.google.com from 192.168.56.102
Aug 25 20:28:52 dnsmasq[2890]: forwarded smartlock.google.com to 1.0.0.1
Aug 25 20:28:52 dnsmasq[2890]: reply smartlock.google.com is <CNAME>
Aug 25 20:28:52 dnsmasq[2890]: reply www3.l.google.com is 172.217.10.78
Aug 25 20:28:52 dnsmasq[2890]: reply smartlock.google.com is <CNAME>
Aug 25 20:28:52 dnsmasq[2890]: reply www3.l.google.com is 2607:f8b0:4006:818::200e
Aug 25 20:28:52 dnsmasq[2890]: query[A] ocsp.pki.goog from 192.168.56.102
Aug 25 20:28:52 dnsmasq[2890]: cached ocsp.pki.goog is <CNAME>
Aug 25 20:28:52 dnsmasq[2890]: cached pki-goog.l.google.com is 172.217.10.131
Aug 25 20:28:52 dnsmasq[2890]: query[AAAA] ocsp.pki.goog from 192.168.56.102
Aug 25 20:28:52 dnsmasq[2890]: cached ocsp.pki.goog is <CNAME>
Aug 25 20:28:52 dnsmasq[2890]: cached pki-goog.l.google.com is 2607:f8b0:4006:818::2003
Aug 25 20:28:52 dnsmasq[2890]: query[A] www.gstatic.com from 192.168.56.102
Aug 25 20:28:52 dnsmasq[2890]: forwarded www.gstatic.com to 1.0.0.1
Aug 25 20:28:52 dnsmasq[2890]: query[AAAA] www.gstatic.com from 192.168.56.102
Aug 25 20:28:52 dnsmasq[2890]: forwarded www.gstatic.com to 1.0.0.1
Aug 25 20:28:52 dnsmasq[2890]: reply www.gstatic.com is 172.217.12.131
Aug 25 20:28:52 dnsmasq[2890]: reply www.gstatic.com is 2607:f8b0:4006:819::2003
Aug 25 20:28:53 dnsmasq[2890]: query[A] www.computerhope.com from 192.168.56.102
Aug 25 20:28:53 dnsmasq[2890]: forwarded www.computerhope.com to 1.0.0.1
Aug 25 20:28:53 dnsmasq[2890]: query[AAAA] www.computerhope.com from 192.168.56.102
Aug 25 20:28:53 dnsmasq[2890]: forwarded www.computerhope.com to 1.0.0.1
Aug 25 20:28:53 dnsmasq[2890]: reply www.computerhope.com is 104.20.56.118
Aug 25 20:28:53 dnsmasq[2890]: reply www.computerhope.com is 104.20.50.118
Aug 25 20:28:53 dnsmasq[2890]: reply www.computerhope.com is 2606:4700:10::6814:3876
Aug 25 20:28:53 dnsmasq[2890]: reply www.computerhope.com is 2606:4700:10::6814:3276
Aug 25 20:28:53 dnsmasq[2890]: query[A] ajax.googleapis.com from 192.168.56.102
Aug 25 20:28:53 dnsmasq[2890]: forwarded ajax.googleapis.com to 1.0.0.1
Aug 25 20:28:53 dnsmasq[2890]: query[AAAA] ajax.googleapis.com from 192.168.56.102
Aug 25 20:28:53 dnsmasq[2890]: forwarded ajax.googleapis.com to 1.0.0.1
Aug 25 20:28:53 dnsmasq[2890]: reply ajax.googleapis.com is <CNAME>
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.12.202
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.3.106
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.6.202
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.6.234
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.7.10
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.9.234
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.10.74
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.10.138
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.11.10
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.11.42
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.12.138
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 172.217.12.170
Aug 25 20:28:53 dnsmasq[2890]: reply ajax.googleapis.com is <CNAME>
Aug 25 20:28:53 dnsmasq[2890]: reply googleapis.l.google.com is 2607:f8b0:4006:810::200a
Aug 25 20:28:55 dnsmasq[2890]: query[A] www.hackerone.com from 192.168.56.102
Aug 25 20:28:55 dnsmasq[2890]: forwarded www.hackerone.com to 1.0.0.1
Aug 25 20:28:55 dnsmasq[2890]: query[AAAA] www.hackerone.com from 192.168.56.102
Aug 25 20:28:55 dnsmasq[2890]: forwarded www.hackerone.com to 1.0.0.1
Aug 25 20:28:55 dnsmasq[2890]: reply www.hackerone.com is 104.16.99.52
Aug 25 20:28:55 dnsmasq[2890]: reply www.hackerone.com is 104.16.100.52
Aug 25 20:28:55 dnsmasq[2890]: reply www.hackerone.com is 2606:4700::6810:6334
Aug 25 20:28:55 dnsmasq[2890]: reply www.hackerone.com is 2606:4700::6810:6434
Aug 25 20:28:56 dnsmasq[2890]: query[A] app-sj17.marketo.com from 192.168.56.102
Aug 25 20:28:56 dnsmasq[2890]: forwarded app-sj17.marketo.com to 1.0.0.1
Aug 25 20:28:56 dnsmasq[2890]: query[AAAA] app-sj17.marketo.com from 192.168.56.102
Aug 25 20:28:56 dnsmasq[2890]: forwarded app-sj17.marketo.com to 1.0.0.1
Aug 25 20:28:56 dnsmasq[2890]: reply app-sj17.marketo.com is <CNAME>
Aug 25 20:28:56 dnsmasq[2890]: reply sj17.mktoedge.com is 104.16.96.80
Aug 25 20:28:56 dnsmasq[2890]: reply sj17.mktoedge.com is 104.16.92.80
Aug 25 20:28:56 dnsmasq[2890]: reply sj17.mktoedge.com is 104.16.93.80
Aug 25 20:28:56 dnsmasq[2890]: reply sj17.mktoedge.com is 104.16.94.80
Aug 25 20:28:56 dnsmasq[2890]: reply sj17.mktoedge.com is 104.16.95.80
Aug 25 20:28:56 dnsmasq[2890]: reply app-sj17.marketo.com is <CNAME>
Aug 25 20:28:56 dnsmasq[2890]: reply sj17.mktoedge.com is NODATA-IPv6
Aug 25 20:28:56 dnsmasq[2890]: query[A] trk.techtarget.com from 192.168.56.102
Aug 25 20:28:56 dnsmasq[2890]: forwarded trk.techtarget.com to 1.0.0.1
Aug 25 20:28:56 dnsmasq[2890]: query[AAAA] trk.techtarget.com from 192.168.56.102
Aug 25 20:28:56 dnsmasq[2890]: forwarded trk.techtarget.com to 1.0.0.1
Aug 25 20:28:56 dnsmasq[2890]: reply trk.techtarget.com is <CNAME>
Aug 25 20:28:56 dnsmasq[2890]: reply trk.techtarget.com.cdngc.net is <CNAME>
Aug 25 20:28:56 dnsmasq[2890]: reply trk.techtarget.com.wtxcdn.com is 157.185.144.122
Aug 25 20:28:56 dnsmasq[2890]: reply trk.techtarget.com is <CNAME>
Aug 25 20:28:56 dnsmasq[2890]: reply trk.techtarget.com.cdngc.net is <CNAME>
Aug 25 20:28:56 dnsmasq[2890]: reply trk.techtarget.com.wtxcdn.com is NODATA-IPv6
Aug 25 20:28:56 dnsmasq[2890]: query[A] ocsp.sectigo.com from 192.168.56.102
Aug 25 20:28:56 dnsmasq[2890]: forwarded ocsp.sectigo.com to 1.0.0.1
Aug 25 20:28:56 dnsmasq[2890]: query[AAAA] ocsp.sectigo.com from 192.168.56.102
Aug 25 20:28:56 dnsmasq[2890]: forwarded ocsp.sectigo.com to 1.0.0.1
Aug 25 20:28:56 dnsmasq[2890]: query[A] errors.hackerone.net from 192.168.56.102
Aug 25 20:28:56 dnsmasq[2890]: forwarded errors.hackerone.net to 1.0.0.1
Aug 25 20:28:56 dnsmasq[2890]: query[AAAA] errors.hackerone.net from 192.168.56.102
Aug 25 20:28:56 dnsmasq[2890]: forwarded errors.hackerone.net to 1.0.0.1
Aug 25 20:28:56 dnsmasq[2890]: reply ocsp.sectigo.com is <CNAME>
Aug 25 20:28:56 dnsmasq[2890]: reply t3j2g9x7.stackpathcdn.com is 151.139.128.14
Aug 25 20:28:56 dnsmasq[2890]: reply ocsp.sectigo.com is <CNAME>
Aug 25 20:28:56 dnsmasq[2890]: reply t3j2g9x7.stackpathcdn.com is 2001:4de0:ac19::1:b:3b
Aug 25 20:28:56 dnsmasq[2890]: reply t3j2g9x7.stackpathcdn.com is 2001:4de0:ac19::1:b:1a
Aug 25 20:28:56 dnsmasq[2890]: reply t3j2g9x7.stackpathcdn.com is 2001:4de0:ac19::1:b:1b
Aug 25 20:28:56 dnsmasq[2890]: reply t3j2g9x7.stackpathcdn.com is 2001:4de0:ac19::1:b:2a
Aug 25 20:28:56 dnsmasq[2890]: reply t3j2g9x7.stackpathcdn.com is 2001:4de0:ac19::1:b:2b
Aug 25 20:28:56 dnsmasq[2890]: reply t3j2g9x7.stackpathcdn.com is 2001:4de0:ac19::1:b:3a
Aug 25 20:28:56 dnsmasq[2890]: reply errors.hackerone.net is 2606:4700::6811:5a04
Aug 25 20:28:56 dnsmasq[2890]: reply errors.hackerone.net is 2606:4700::6811:5b04
Aug 25 20:28:56 dnsmasq[2890]: reply errors.hackerone.net is 104.17.90.4
Aug 25 20:28:56 dnsmasq[2890]: reply errors.hackerone.net is 104.17.91.4
Aug 25 20:28:58 dnsmasq[2890]: query[A] codescracker.com from 192.168.56.102
Aug 25 20:28:58 dnsmasq[2890]: forwarded codescracker.com to 1.0.0.1
Aug 25 20:28:58 dnsmasq[2890]: query[AAAA] codescracker.com from 192.168.56.102
Aug 25 20:28:58 dnsmasq[2890]: forwarded codescracker.com to 1.0.0.1
Aug 25 20:28:58 dnsmasq[2890]: reply codescracker.com is 132.148.244.46
Aug 25 20:28:58 dnsmasq[2890]: reply codescracker.com is NODATA-IPv6
Aug 25 20:28:59 dnsmasq[2890]: query[A] static.addtoany.com from 192.168.56.102
Aug 25 20:28:59 dnsmasq[2890]: forwarded static.addtoany.com to 1.0.0.1
Aug 25 20:28:59 dnsmasq[2890]: query[AAAA] static.addtoany.com from 192.168.56.102
Aug 25 20:28:59 dnsmasq[2890]: forwarded static.addtoany.com to 1.0.0.1
Aug 25 20:28:59 dnsmasq[2890]: reply static.addtoany.com is 104.20.110.39
Aug 25 20:28:59 dnsmasq[2890]: reply static.addtoany.com is 104.20.111.39
Aug 25 20:28:59 dnsmasq[2890]: reply static.addtoany.com is 2606:4700:10::6814:6f27
Aug 25 20:28:59 dnsmasq[2890]: reply static.addtoany.com is 2606:4700:10::6814:6e27
Aug 25 20:29:18 dnsmasq[2890]: query[A] null-byte.wonderhowto.com from 192.168.56.102
Aug 25 20:29:18 dnsmasq[2890]: forwarded null-byte.wonderhowto.com to 1.0.0.1
Aug 25 20:29:18 dnsmasq[2890]: query[AAAA] null-byte.wonderhowto.com from 192.168.56.102
Aug 25 20:29:18 dnsmasq[2890]: forwarded null-byte.wonderhowto.com to 1.0.0.1
Aug 25 20:29:18 dnsmasq[2890]: reply null-byte.wonderhowto.com is 104.193.19.59
Aug 25 20:29:18 dnsmasq[2890]: reply null-byte.wonderhowto.com is NODATA-IPv6
Aug 25 20:29:18 dnsmasq[2890]: query[A] img.wonderhowto.com from 192.168.56.102
Aug 25 20:29:18 dnsmasq[2890]: forwarded img.wonderhowto.com to 1.0.0.1
Aug 25 20:29:18 dnsmasq[2890]: query[AAAA] img.wonderhowto.com from 192.168.56.102
Aug 25 20:29:18 dnsmasq[2890]: forwarded img.wonderhowto.com to 1.0.0.1
Aug 25 20:29:18 dnsmasq[2890]: query[A] fonts.googleapis.com from 192.168.56.102
Aug 25 20:29:18 dnsmasq[2890]: forwarded fonts.googleapis.com to 1.0.0.1
Aug 25 20:29:18 dnsmasq[2890]: query[AAAA] fonts.googleapis.com from 192.168.56.102
Aug 25 20:29:18 dnsmasq[2890]: forwarded fonts.googleapis.com to 1.0.0.1
Aug 25 20:29:18 dnsmasq[2890]: query[A] ads.servebom.com from 192.168.56.102
Aug 25 20:29:18 dnsmasq[2890]: /etc/pihole/gravity.list ads.servebom.com is 0.0.0.0
Aug 25 20:29:18 dnsmasq[2890]: query[AAAA] ads.servebom.com from 192.168.56.102
Aug 25 20:29:18 dnsmasq[2890]: /etc/pihole/gravity.list ads.servebom.com is 0.0.0.0
Aug 25 20:29:18 dnsmasq[2890]: reply img.wonderhowto.com is <CNAME>
Aug 25 20:29:18 dnsmasq[2890]: reply cds.d6b8y6w3.hwcdn.net is 69.16.175.10
Aug 25 20:29:18 dnsmasq[2890]: reply cds.d6b8y6w3.hwcdn.net is 69.16.175.42
Aug 25 20:29:18 dnsmasq[2890]: reply img.wonderhowto.com is <CNAME>
Aug 25 20:29:18 dnsmasq[2890]: reply cds.d6b8y6w3.hwcdn.net is NODATA-IPv6
Aug 25 20:29:18 dnsmasq[2890]: reply fonts.googleapis.com is <CNAME>
Aug 25 20:29:18 dnsmasq[2890]: reply googleadapis.l.google.com is 172.217.12.138
Aug 25 20:29:18 dnsmasq[2890]: reply fonts.googleapis.com is <CNAME>
Aug 25 20:29:18 dnsmasq[2890]: reply googleadapis.l.google.com is 2607:f8b0:4006:802::200a
Aug 25 20:29:19 dnsmasq[2890]: query[A] fonts.gstatic.com from 192.168.56.102
Aug 25 20:29:19 dnsmasq[2890]: forwarded fonts.gstatic.com to 1.0.0.1
Aug 25 20:29:19 dnsmasq[2890]: query[AAAA] fonts.gstatic.com from 192.168.56.102
Aug 25 20:29:19 dnsmasq[2890]: forwarded fonts.gstatic.com to 1.0.0.1
Aug 25 20:29:19 dnsmasq[2890]: reply fonts.gstatic.com is <CNAME>
Aug 25 20:29:19 dnsmasq[2890]: reply gstaticadssl.l.google.com is 172.217.11.35
Aug 25 20:29:19 dnsmasq[2890]: reply fonts.gstatic.com is <CNAME>
Aug 25 20:29:19 dnsmasq[2890]: reply gstaticadssl.l.google.com is 2607:f8b0:4006:815::2003
```

# attacker (me) enumerating XSS vulns in DNS front-end web app (pi-hole)
# while read payload; do dig "$payload" 192.168.56.101; done </tmp/xsspayloads.txt

```bash
Aug 25 20:47:19 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:19 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:47:19 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:19 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:25 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:25 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:47:25 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:25 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:31 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:31 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:47:31 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:31 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:34 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:34 dnsmasq[2890]: forwarded <name unprintable> to 1.0.0.1
Aug 25 20:47:34 dnsmasq[2890]: forwarded <name unprintable> to 1.1.1.1
Aug 25 20:47:34 dnsmasq[2890]: reply <name unprintable> is NXDOMAIN
Aug 25 20:47:34 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:34 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:37 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:37 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:47:37 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:37 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:43 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:43 dnsmasq[2890]: forwarded <name unprintable> to 1.0.0.1
Aug 25 20:47:43 dnsmasq[2890]: reply <name unprintable> is NXDOMAIN
Aug 25 20:47:43 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:43 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:46 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:46 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:47:46 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:46 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:49 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:49 dnsmasq[2890]: forwarded <name unprintable> to 1.0.0.1
Aug 25 20:47:49 dnsmasq[2890]: reply <name unprintable> is NXDOMAIN
Aug 25 20:47:49 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:49 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:52 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:52 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:47:52 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:52 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:55 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:55 dnsmasq[2890]: forwarded <name unprintable> to 1.0.0.1
Aug 25 20:47:55 dnsmasq[2890]: reply <name unprintable> is NXDOMAIN
Aug 25 20:47:55 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:55 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:47:58 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:47:58 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:47:58 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:47:58 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:48:01 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:48:01 dnsmasq[2890]: forwarded <name unprintable> to 1.0.0.1
Aug 25 20:48:01 dnsmasq[2890]: reply <name unprintable> is NXDOMAIN
Aug 25 20:48:01 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:48:01 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:48:04 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:48:04 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:48:04 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:48:04 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:48:10 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:48:10 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:48:10 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:48:10 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:48:13 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:48:13 dnsmasq[2890]: forwarded <name unprintable> to 1.0.0.1
Aug 25 20:48:13 dnsmasq[2890]: reply <name unprintable> is NXDOMAIN
Aug 25 20:48:13 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:48:13 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:49:21 dnsmasq[2890]: query[A] null-byte.wonderhowto.com from 192.168.56.102
Aug 25 20:49:21 dnsmasq[2890]: cached null-byte.wonderhowto.com is 104.193.19.59
Aug 25 20:51:03 dnsmasq[2890]: query[A] pi-hole.net from 127.0.0.1
Aug 25 20:51:03 dnsmasq[2890]: forwarded pi-hole.net to 1.0.0.1
Aug 25 20:51:03 dnsmasq[2890]: query[AAAA] pi-hole.net from 127.0.0.1
Aug 25 20:51:03 dnsmasq[2890]: forwarded pi-hole.net to 1.0.0.1
Aug 25 20:51:04 dnsmasq[2890]: reply pi-hole.net is 206.189.252.21
Aug 25 20:51:04 dnsmasq[2890]: reply pi-hole.net is 2604:a880:400:d0::1071:1
Aug 25 20:52:15 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:52:15 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:52:15 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:52:15 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:52:18 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:52:18 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:52:18 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:52:18 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:52:21 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:52:21 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:52:21 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:52:21 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:52:24 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:52:24 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:52:24 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:52:24 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:52:56 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:52:56 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:52:56 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:52:56 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:52:59 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:52:59 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:52:59 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:52:59 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:53:02 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:53:02 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:53:02 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:53:02 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:53:05 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:53:05 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:53:05 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:53:05 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:53:10 dnsmasq[2890]: query[A] safebrowsing.googleapis.com from 127.0.0.1
Aug 25 20:53:10 dnsmasq[2890]: forwarded safebrowsing.googleapis.com to 1.0.0.1
Aug 25 20:53:10 dnsmasq[2890]: reply safebrowsing.googleapis.com is 172.217.9.234
Aug 25 20:53:23 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:53:23 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:53:23 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:53:23 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:53:26 dnsmasq[2890]: query[A] <name unprintable> from 192.168.56.102
Aug 25 20:53:26 dnsmasq[2890]: cached <name unprintable> is NXDOMAIN
Aug 25 20:53:26 dnsmasq[2890]: query[A] 192.168.56.101 from 192.168.56.102
Aug 25 20:53:26 dnsmasq[2890]: cached 192.168.56.101 is NXDOMAIN
Aug 25 20:53:51 dnsmasq[2890]: query[A] www.paypal.com from 127.0.0.1
Aug 25 20:53:51 dnsmasq[2890]: cached www.paypal.com is <CNAME>
Aug 25 20:53:51 dnsmasq[2890]: cached www.glb.paypal.com is <CNAME>
Aug 25 20:53:51 dnsmasq[2890]: forwarded www.paypal.com to 1.0.0.1
Aug 25 20:53:51 dnsmasq[2890]: reply www.paypal.com is <CNAME>
Aug 25 20:53:51 dnsmasq[2890]: reply www.glb.paypal.com is <CNAME>
Aug 25 20:53:51 dnsmasq[2890]: reply www.paypal.com.edgekey.net is <CNAME>
Aug 25 20:53:51 dnsmasq[2890]: reply e16973.a.akamaiedge.net is 23.221.48.119
Aug 25 20:54:04 dnsmasq[2890]: query[A] docs.pi-hole.net from 127.0.0.1
Aug 25 20:54:04 dnsmasq[2890]: forwarded docs.pi-hole.net to 1.0.0.1
Aug 25 20:54:04 dnsmasq[2890]: query[AAAA] docs.pi-hole.net from 127.0.0.1
Aug 25 20:54:04 dnsmasq[2890]: forwarded docs.pi-hole.net to 1.0.0.1
Aug 25 20:54:04 dnsmasq[2890]: reply docs.pi-hole.net is <CNAME>
Aug 25 20:54:04 dnsmasq[2890]: reply pi-hole.github.io is 185.199.110.153
Aug 25 20:54:04 dnsmasq[2890]: reply pi-hole.github.io is 185.199.111.153
Aug 25 20:54:04 dnsmasq[2890]: reply pi-hole.github.io is 185.199.108.153
Aug 25 20:54:04 dnsmasq[2890]: reply pi-hole.github.io is 185.199.109.153
Aug 25 20:54:04 dnsmasq[2890]: reply docs.pi-hole.net is <CNAME>
Aug 25 20:54:04 dnsmasq[2890]: reply pi-hole.github.io is NODATA-IPv6
Aug 25 20:54:21 dnsmasq[2890]: query[A] null-byte.wonderhowto.com from 192.168.56.102
Aug 25 20:54:21 dnsmasq[2890]: cached null-byte.wonderhowto.com is 104.193.19.59
Aug 25 20:55:10 dnsmasq[2890]: query[A] pi-hole.net from 127.0.0.1
Aug 25 20:55:10 dnsmasq[2890]: cached pi-hole.net is 206.189.252.21
Aug 25 20:55:14 dnsmasq[2890]: query[A] www.paypal.com from 127.0.0.1
Aug 25 20:55:14 dnsmasq[2890]: cached www.paypal.com is <CNAME>
Aug 25 20:55:14 dnsmasq[2890]: cached www.glb.paypal.com is <CNAME>
Aug 25 20:55:14 dnsmasq[2890]: forwarded www.paypal.com to 1.0.0.1
Aug 25 20:55:14 dnsmasq[2890]: reply www.paypal.com is <CNAME>
Aug 25 20:55:14 dnsmasq[2890]: reply www.glb.paypal.com is <CNAME>
Aug 25 20:55:14 dnsmasq[2890]: reply www.paypal.com.edgekey.net is <CNAME>
Aug 25 20:55:14 dnsmasq[2890]: reply e16973.a.akamaiedge.net is 23.221.48.119
Aug 25 20:55:34 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:34 dnsmasq[2890]: forwarded api.github.com to 1.0.0.1
Aug 25 20:55:34 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:34 dnsmasq[2890]: forwarded api.github.com to 1.0.0.1
Aug 25 20:55:34 dnsmasq[2890]: reply api.github.com is 140.82.114.5
Aug 25 20:55:34 dnsmasq[2890]: reply api.github.com is NODATA-IPv6
Aug 25 20:55:35 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:35 dnsmasq[2890]: cached api.github.com is 140.82.114.5
Aug 25 20:55:35 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:35 dnsmasq[2890]: cached api.github.com is NODATA-IPv6
Aug 25 20:55:35 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:35 dnsmasq[2890]: cached api.github.com is 140.82.114.5
Aug 25 20:55:35 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:35 dnsmasq[2890]: cached api.github.com is NODATA-IPv6
Aug 25 20:55:35 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:35 dnsmasq[2890]: cached api.github.com is 140.82.114.5
Aug 25 20:55:35 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:35 dnsmasq[2890]: cached api.github.com is NODATA-IPv6
Aug 25 20:55:35 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:35 dnsmasq[2890]: cached api.github.com is 140.82.114.5
Aug 25 20:55:35 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:35 dnsmasq[2890]: cached api.github.com is NODATA-IPv6
Aug 25 20:55:36 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:36 dnsmasq[2890]: cached api.github.com is 140.82.114.5
Aug 25 20:55:36 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:36 dnsmasq[2890]: cached api.github.com is NODATA-IPv6
Aug 25 20:55:36 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:36 dnsmasq[2890]: cached api.github.com is 140.82.114.5
Aug 25 20:55:36 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:36 dnsmasq[2890]: cached api.github.com is NODATA-IPv6
Aug 25 20:55:36 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:36 dnsmasq[2890]: cached api.github.com is 140.82.114.5
Aug 25 20:55:36 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:36 dnsmasq[2890]: cached api.github.com is NODATA-IPv6
Aug 25 20:55:36 dnsmasq[2890]: query[A] api.github.com from 127.0.0.1
Aug 25 20:55:36 dnsmasq[2890]: cached api.github.com is 140.82.114.5
Aug 25 20:55:36 dnsmasq[2890]: query[AAAA] api.github.com from 127.0.0.1
Aug 25 20:55:36 dnsmasq[2890]: cached api.github.com is NODATA-IPv6
Aug 25 20:55:39 dnsmasq[2890]: query[A] apricorni.vardtorg.ru from 127.0.0.1
Aug 25 20:55:39 dnsmasq[2890]: /etc/pihole/gravity.list apricorni.vardtorg.ru is 0.0.0.0
Aug 25 20:55:39 dnsmasq[2890]: query[A] apricorni.vardtorg.ru from 192.168.56.101
Aug 25 20:55:39 dnsmasq[2890]: /etc/pihole/gravity.list apricorni.vardtorg.ru is 0.0.0.0
```
![DNS](https://learndotresources.s3.amazonaws.com/workshop/5d42f98c2d669d000414097d/xss1.png)
