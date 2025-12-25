# Monitoring web site with Prometheus Black Box Exporter and NGINX Exporter & visualise in Grafana Dashboards
[!nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)


## Nginx Exporrtetr Docker Command

docker run -d --name nginx-exporter --restart unless-stopped   --network host   nginx/nginx-prometheus-exporter:latest   -nginx.scrape-uri http://127.0.0.1/stub_status

