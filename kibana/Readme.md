# Elastic Search Basics:
## Docker pull:
- docker pull docker.elastic.co/kibana/kibana:7.9.2
## Docker run {"3292a5ba68f4" as ElasticSearch container id}:
- docker run --link 3292a5ba68f4:elasticsearch -p 5601:5601 docker.elastic.co/kibana/kibana:7.6.1


## To create index {user-1} and add data
- localhost:5601