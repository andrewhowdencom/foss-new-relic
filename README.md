# FOSS New Relic

## Features

### Application Monitoring

| Feature | Alternative |
|---------|-------------|
| Response Time, Throughput, and Error Rates | Prometheus + exporters. |
| Application Histograms & Percentiles | Prometheus, Grafana |
| Most Time-Consuming Transactions | Elasticsearch, Logstash and Kibana. Maybe Prometheus labels |
| Performance of External Services | Native application metrics, + Prometheus exporter | 
| Transaction Metrics and Traces | Opentracing (like, zipkin) |
| Thread Profile | Tideways profiler + xhprof |
| Cross Application Tracing | Opentracing | 
| Track Key Business Transactions | Prometheus + AlertManager. Grafana |
| Service Map | ? OpenTracing maybe. |
| Deployment Analysis, History, and Comparison | Prometehus Labels |

### Database Monitoring 

| Feature | Alternative | 
|---------|-------------|
| Time Spent in Database Calls | Prometheus exporter |
| Database Call Response Time and Throughput | Prometheus exporter | 
| Slow SQL Report | MySQL SlowLog query + ELK |
| Filter to a specific database/cache type | Kibana |
| See and search all database/cache operations | MySQL Log + ELK |

### Availability & Error Monitoring

| Feature | Alternative | 
|----------|-------------|
| Alerting | AlertManager (Prometheus) | 
| Availability Monitoring | Prometehus blackbox exporter | 
 
### Reports

Grafana for everything

### Team Collaboration

For prometheus, reverse proxy for NGINX that has .htaccess files. 


