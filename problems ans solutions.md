# Hadoop-problems-and-their-solutions
hadoop

problem:
INFO ipc.Client: Retrying connect to server: 0.0.0.0/0.0.0.0:8032. Already tried 8 time(s); retry policy is RetryUpToMaximumCountWithFixedSleep(maxRetries=10, sleepTime=1000 MILLISECONDS)

solution
yum install ntp ntpdate
ntpdate pool.ntp.org
/etc/init.d/ntpd start
chkconfig ntpd on
restart system/server
