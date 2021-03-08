# diff
* do not take account spaces
```
diff -bBEw  logstash-files/apache.txt /etc/logstash/conf.d/apache.conf
4c4
< 		path => "/Users/imtiazahmad/elasticsearch_course/data/logs/logs"
---
>     path => "/home/centos/logs/apache.log"
23c22
< 		locale => en
---
>     local => en
39c37
< 		codec => dots
---
>     code => dots
```
