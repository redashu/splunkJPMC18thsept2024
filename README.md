## Splunk 

### training plan 

<img src="plan.png">

### aws console link

[click_here](https://delvexdrive.signin.aws.amazon.com/console)

### creating account in splunk.com 

[click_here](https://www.splunk.com/en_us/download/splunk-cloud.html)

### sample data for testing in splunk 

[click_here](https://delvex-software-center.s3.ap-south-1.amazonaws.com/splunk-softwares/Practice_Data.zip)


## setup splunk universal forwarder in linux vm 

```
wget -O splunkforwarder-9.3.1-0b8d769cb912.x86_64.rpm "https://download.splunk.com/products/universalforwarder/releases/9.3.1/linux/splunkforwarder-9.3.1-0b8d769cb912.x86_64.rpm"

===> verify 
cd /opt/splunkforwarder/
[root@ip-172-31-28-99 splunkforwarder]# ls
LICENSE.txt        bin            etc  include  license-eula.txt  share                                                         swidtag
README-splunk.txt  copyright.txt  ftr  lib      openssl           splunkforwarder-9.3.1-0b8d769cb912-linux-2.6-x86_64-manifest  uf
[root@ip-172-31-28-99 splunkforwarder]# 

```

