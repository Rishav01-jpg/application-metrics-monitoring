# Application Metrics Monitoring

Java application monitoring using Prometheus and Grafana.

## Technologies
- Java 21 and Maven
- Prometheus 2.54.0
- Grafana 11.1.4
- Node Exporter
- Pushgateway

## Metrics
The Java application exposes metrics at `/metrics` on port 1234. The custom counter `hello_worlds_total` tracks Hello World requests.

## Architecture
Java Application -> Prometheus -> Grafana

## Project folders
- `java_simple/` - Java application source code
- `prometheus/` - Prometheus configuration
- `systemd/` - Java application service configuration

## Attribution
Java example based on https://github.com/RobustPerception/java_examples
