# 1.Install node_exporter
# 2.check node exporte from http://x.x.x.x:9100/
# 3./opt/prometheus ----> comment node_exporter
# 4. docker compose up -d
# 5. docker compose ps
    http://x.x.x.x:9090 ---- prometheus
    http://x.x.x.x:3000 ---- grafana
    garafana user & pass : admin
# 6. add dashboards from https://grafana.com/grafana/dashboards/ to grafana
Node exporter                                  1860 11074
PostgreSQL Queries Overview (Designed for PMM) 10017
PostgreSQL Performance Analysis               10521
Windows Exporter                              10467  10171
Cadvisor                                      13112  14282
Postgress statistic                           13494
New Dashboard Nodeexporter                    11074
Black box          13659 7587
Nginx exporter                                 12708
Bind exporter                                  1666
mysql exporter                                   7362 


=====================

Lighthouse Metrics Report:10288
Docker Monitoring:893
OpenVPN Connection Monitoring:10562
Kubernetes cluster overview:11802
