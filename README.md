# spring-cloud-dataflow-docker-compose
simple setup of SCDF with Docker Compose

To start SCDF with prom-proxy run:
"docker-compose -f ./docker-compose.yml -f ./docker-compose-prometheus.yml up"

To start SCDF with pushgateway run:
"docker-compose -f ./docker-compose.yml -f ./docker-compose-prometheus-pushgateway.yml up"
