# Writes from a kafka queue to elasticsearch
This pattern is rarely needed. I just need a way to wam-jamble some messages into kibana.

## Deps
```
wget https://artifacts.elastic.co/downloads/kibana/kibana-6.1.2-darwin-x86_64.tar.gz
wget https://artifacts.elastic.co/downloads/logstash/logstash-6.1.1.tar.gz 

```

## 
> bin/logstash -f logstash.conf