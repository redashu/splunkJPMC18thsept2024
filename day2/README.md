# splunkJPMC18thsept2024

## Revision 

<img src="rev1.png">

### splunk arch 

<img src="rev2.png">

## verify splunk forwarder status 

```
ec2-user@ip-172-31-28-99 ~]$ sudo -i

[root@ip-172-31-28-99 ~]# /opt/splunkforwarder/bin/splunk status
Warning: Attempting to revert the SPLUNK_HOME ownership
Warning: Executing "chown -R splunkfwd:splunkfwd /opt/splunkforwarder"
splunkd is running (PID: 2432).
splunk helpers are running (PIDs: 2502).
[root@ip-172-31-28-99 ~]# 

```

### webapp logs on server 

```
 cd /var/log/httpd/
[root@ip-172-31-28-99 httpd]# ls
access_log  error_log
[root@ip-172-31-28-99 httpd]# 

```

