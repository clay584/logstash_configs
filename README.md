logstash_configs
================

Logstash configs for v1.3.3 standalone

These were written for logstash running on Centos 6.4

File locations:
logstash jar file goes in /opt/logstash

config file goes in /etc/logstash

patterns folder goes in /opt/logstash

create var/log/logstash for all logs, data, and sincedb file

init script goes in /etc/init.d

to initialize init script run "chkconfig --add logstash"

to turn on, run "chkconfig logstash on"

to start/stop: "service logstash {start|stop|restart}"
