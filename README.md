# prometheus-docker-compose

Brings up prometheus with [static targets](prometheus_config/prometheus.yml) as [prometheus](https://github.com/prometheus/prometheus) itself and [node-exporter](https://github.com/prometheus/node_exporter).

## Motivation

To play around prometheus, [promql](https://prometheus.io/docs/prometheus/latest/querying/basics/) and node-exporter metrics

## Usage

```go
docker-compose up -d
```

To reload after prometheus config changes

```zsh
curl -X POST http://localhost:9090/-/reload
```

- [Access Prometheus](http://localhost:9090/)
- [Access Node Exporter](http://localhost:9100)
