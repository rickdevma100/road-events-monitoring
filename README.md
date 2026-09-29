# Road Events Monitoring

Prometheus monitoring and Grafana visualization configs for Road Events.

## Components
- `manifests/service-monitor.yaml`: Prometheus ServiceMonitor targeting `road-events-api` endpoints in namespace `road-events`.
- `dashboards/road-events-overview.json`: Grafana dashboard tracking API request rates, event ingestion, and system health.