# elk-docker-pem
This is an elk docker based deployment which includes index-patterns and elasticsearch objects (searches, visualizations and dashboards) for F5 PEM and DNS reporting. 

Even if everything is already included in the data directory, jsons are also provided if you want to deploy a brand new elk and update it with index patterns and elasticsearch objects.

# Content of Repository

## conf directory
This is the directory containing all the configuration files

### elasticsearch.yml

Elasticsearch config file

### logstash.yml

Logstash configuration file

### logstash_main.conf

Logstash pipeline config file which includes the ports logstash listens to and how the data are processed before they're sent to elastic search

### kibana.yml

Kibana configuration file.

## json Files

Directory containing the json files of index patterns and elasticsearch objects 

## data

Directory containing Elastic Search data (patterns and objects already loaded)
