# Prometheus

Prometheus / Grafana / Alertmanager with exporters example. To start run `docker-compose up -d` in root directory of the repository. This will setup Prometheus monitoring:

* CAdvisor - monitoring of docker engine containers
* Node exporter - monitoring of VM resources
* Blackbox exporter - monitoring of Kibana/Elasticsearch URLs

Available services:

 * Prometheus: 192.168.44.44:9090
 * Grafana:  192.168.44.44:3000 (login - admin:panda)
 * Alertmanager: 192.168.44.44:9093
 * Cadvisor: 192.168.44.44:8080
 * Node exporter 192.168.44.44:9100
 * Blackbox exporter: 192.168.44.44:9115