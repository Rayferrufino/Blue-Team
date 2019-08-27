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
