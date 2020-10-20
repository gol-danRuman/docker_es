@author Ruman dangol, rumancha12@gmail.com

.docker-compose file description
 
- After docker-compose up add index
- curl -X PUT "localhost:9200/twitter?pretty" to create index twitter
- curl -X PUT "localhost:9200/user-1/_doc/1?pretty" -H 'Content-Type: application/json' -d'
{
  "name": "ruman dangol"
}
'
 To add document in index customer
- After creating index go to kibana and Go to setting kibana index patter create new index pattern 
- Go to discover to search the json document


