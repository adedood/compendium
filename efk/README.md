## EFK experiment

Prerequisites: Docker

To start containers, run `docker-compose up`

To generate httpd Access Logs `curl http://localhost:80/`

Confirm logs from Kibana, http://localhost:5601/, create fluentd-* index. 