# Prometheus Example
A simple Prometheus example using docker-compose.

### Requirements
* docker-compose

### Usage
1. `git clone https://github.com/adam1141/prometheus-example`
2. `cd prometheus-example`
3. `docker-compose up -d`
4. visit prometheus at -> http://localhost:9090
5. wait a few seconds, run queries on node_* to get familiar
6. after finishing, run `docker-compose down` to remove created containers
  
* more on Prometheus at: https://prometheus.io/docs/introduction/overview