# logstash-data-pipeline
This project shows how to migrade data from/to elasticsearch with pipeline

## Install java

  `yum install java-1.8.0-openjdk -y`
  
## Install logstash

  `wget https://artifacts.elastic.co/downloads/logstash/logstash-7.6.2.tar.gz`
  `tar -xvf logstash-7.6.2.tar.gz`

## Install plugings
  `cd logstash-7.6.2/bin/`
  
  `./logstash-plugin install logstash-input-elasticsearch`

  `./logstash-plugin install logstash-output-elasticsearch`

## Config pipeline
  `vi /root/kfk_credito.memoria_operacao.conf`
  
  `vi /root/logstash-7.6.2/config/pipelines.yml`

## Run pipeline

  `logstash -e`
  or
  `logstash --config.reload.automatic`
  
