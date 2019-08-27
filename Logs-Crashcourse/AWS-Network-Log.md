# Reading network logs

![AWS-capture](https://media.amazonwebservices.com/blog/2015/flow_see_a_stream_2.png)

# AWS Flow Log Syntax 
```bash
<version> <account-id> <interface-id> <srcaddr> <dstaddr> <srcport> <dstport> <protocol> <packets> <bytes> <start> <end> <action> <log-status>
```

| Field         | Description   |
| ------------- |:-------------:| 
| version       | The VPC Flow Logs version |
| account-id    | The AWS account ID for the flow log.      |
| interface-id  | The ID of the network interface for which the traffic is recorded.    |
| srcaddr       | The source IPv4 or IPv6 address. The IPv4 address of the network interface is always its private IPv4 address. |
| dstaddr       | The destination IPv4 or IPv6 address. The IPv4 address of the network interface is always its private IPv4 address.|     
| srcport       | The source port of the traffic.      |
| dstport       |The destination port of the traffic. |
| protocol      | The IANA protocol number of the traffic      |
| packets       | The number of packets transferred during the capture window.      |
| bytes         | The number of bytes transferred during the capture window.      |
| start         | The time, in Unix seconds, of the start of the capture window.      |
| end           | The time, in Unix seconds, of the end of the capture window. |
| action        | The action associated with the traffic:ACCEPT REJECT.|
| log-status    | The logging status of the flow log: OK: Data is logging normally to the chosen destinations. NODATA SKIPDATA      |


# Flow Log Record Examples
## Flow Log Records for Accepted and Rejected Traffic

The following is an example of a flow log record in which SSH traffic (destination port 22, TCP protocol) to network interface eni-abc123de in account 123456789010 was allowed:
```bash
2 123456789010 eni-abc123de 172.31.16.139 172.31.16.21 20641 22 6 20 4249 1418530010 1418530070 ACCEPT OK
```

![capture](https://learn.fullstackacademy.com/workshop/5d42f584e9d1e50004b78539/content/5d42f6eaf19fa200045d058e/text)
