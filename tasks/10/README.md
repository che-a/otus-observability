## Занятие 10. Prometheus как новый виток систем мониторинга

#### Ресурсы по Prometheus
[Официальный сайт](https://prometheus.io/)
[Документация](https://prometheus.io/docs/introduction/overview/)
[Последний релиз](https://github.com/prometheus/prometheus/releases/latest)

#### Адреса для подключений


| Название | Адрес         | Порт гостя | Порт хоста |          URL          | Назначение          |
|----------|---------------|------------|------------|-----------------------|---------------------|
| prom-srv | 192.168.50.10 | 9090       | 9090       | http://127.0.0.1:9090 | Prometheus          |
| prom-srv | 192.168.50.10 | 9093       | 9093       | http://127.0.0.1:9093 | Alertmanager        |
| prom-srv | 192.168.50.10 | 9100       | 9100       | http://127.0.0.1:9100 | node_exporter       |
| web1     | 192.168.50.20 | 80         | 8080       | http://127.0.0.1:8080 | nginx               |
| web1     | 192.168.50.20 | 8080       | 8081       | http://127.0.0.1:8081 | nginx_exporter_stat |
| web1     | 192.168.50.20 | 9100       | 9101       | http://127.0.0.1:9101 | node_exporter       |
| web1     | 192.168.50.20 | 9113       | 9113       | http://127.0.0.1:9113 | nginx_exporter      |
