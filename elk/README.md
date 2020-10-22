### Notes
Make sure Docker Engine is allotted at least 4GiB of memory.

```
docker-compose up
curl -X GET "localhost:9200/_cat/nodes?v&pretty"
docker-compose restart <service name>   # to restart a container started by docker-compose
```
Open Kibana to load sample data and interact with the cluster: http://localhost:5601.

Tear down
`docker-compose down -v`