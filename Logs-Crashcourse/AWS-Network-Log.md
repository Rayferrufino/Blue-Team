# Reading network logs

![AWS-capture](https://media.amazonwebservices.com/blog/2015/flow_see_a_stream_2.png)

# AWS Flow Log Syntax 
```bash
<version> <account-id> <interface-id> <srcaddr> <dstaddr> <srcport> <dstport> <protocol> <packets> <bytes> <start> <end> <action> <log-status>
```

| Field         | Description   |
| ------------- |:-------------:| 
| version       | right-aligned |
| account-id    | centered      |
| interface-id  | are neat      |
