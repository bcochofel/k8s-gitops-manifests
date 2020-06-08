# Observability Stack

Components:
- Prometheus Operator
- Thanos
- Grafana Loki
- Jaeger Operator

## Prometheus Operator

Prometheus Operator deploys:

- Alertmanager
- Grafana
- Prometheus (with Thanos sidecar)

### Grafana

Credentials (created with Secret):

- username: admin
- password: password

Datasources:

- Thanos (for Thanos Querier)
- Prometheus
- Loki

## Thanos

Thanos only deploys Thanos Querier. Querier gets metrics from Prometheus
replicas.

## Loki

Loki deploys with promtail.

## Jaeger Operator

Deploys AllInOne Jaeger instance.
