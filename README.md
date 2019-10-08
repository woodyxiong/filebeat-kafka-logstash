# filebeat-kafka-logstash

搭建filebeat->logstash->elasticsearch

## Logstash搭建
将`logstash.conf`送进`/usr/share/logstash/pipeline/logstash.conf`，在启动Logstash容器的时候，会读取这个配置文件并执行。

## filebeat搭建
将`filebeat.yml`送进容器的任何一个地方，执行`filebeat -c filebeat.yml -e`
