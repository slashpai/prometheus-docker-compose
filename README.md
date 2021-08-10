# prometheus-docker-compose

Brings up prometheus with [static targets](prometheus_config/prometheus.yml) as [prometheus](https://github.com/prometheus/prometheus) itself and [node-exporter](https://github.com/prometheus/node_exporter).

## Motivation

To play around prometheus, [promql](https://prometheus.io/docs/prometheus/latest/querying/basics/) and node-exporter metrics

## Usage

```go
docker-compose up -d
```

- [Access Prometheus](http://localhost:9090/)
- [Access Node Exporter](http://localhost:9100)
- [Access Grafana](http://localhost:3000)