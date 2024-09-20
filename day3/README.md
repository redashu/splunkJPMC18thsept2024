## Revision 

### Splunk CLuster with HA 

<img src="cls.png">

### Indexer and Search head more info 

<img src="searchh.png">

### Indexing and Parsing queue 

<img src="q1.png">

## checking status

```
/opt/splunkforwarder/bin/splunk status

====>
/opt/splunkforwarder/bin/splunk list  monitor
```

## users in Splunk 

<img src="spu.png">

## macros in Splunk 

<img src="mc1.png">

### we can use macros using ``

```
index="main" host="ip-172-31-16-190.ec2.internal" | `web_timestamp_clientIP`
```

## creating dashboard 

<img src="dash1.png">

## alerts in Splunk 

<img src="alt.png">

### root login failed attempt ips 

```
index="ashu_security" sourcetype=linux_secure root Fail* | rex field=_raw "^\w+\s+\w+\s+\d+\s+\d+\s+\d+:\d+:\d+\s+\w+\d+\s+\w+\[\d+\]:\s+\w+\s+\w+\s+\w+\s+\w+\s+\w+\s+(?P<hacker_ip>[^ ]+)" | table _time , hacker_ip
```



