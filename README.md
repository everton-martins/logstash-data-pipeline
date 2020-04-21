# logstash-data-pipeline
This project shows how to migrade data from/to elasticsearch with pipeline

## Install java

  `yum install java-1.8.0-openjdk -y`
  
  
## Install plugings
  `logstash-plugin install logstash-input-elasticsearch`

  `logstash-plugin install logstash-output-elasticsearch`

## Config pipeline
  `vi /root/kfk_credito.memoria_operacao.conf`
  
  `vi /usr/share/logstash/config/pipelines.yml`

## Run pipeline

  `logstash -e`
  
