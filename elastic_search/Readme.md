# Elastic Search Basics:
## Docker pull:
- docker pull docker.elastic.co/elasticsearch/elasticsearch:7.9.2
## Docker run:
- docker run -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:7.9.2

## To create index {user-1} and add data
- curl -X PUT "localhost:9200/user-1/_doc/1?pretty" -H 'Content-Type: application/json' -d'
{
  "name": "ruman dangol"
}
'