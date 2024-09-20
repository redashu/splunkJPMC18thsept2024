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
