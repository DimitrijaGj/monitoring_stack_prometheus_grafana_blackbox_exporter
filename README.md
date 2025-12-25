# Monitoring web site with Prometheus Black Box Exporter and NGINX Exporter & visualise in Grafana Dashboards

![prometheus](https://img.shields.io/badge/Prometheus-000000?style=for-the-badge&logo=prometheus&labelColor=000000)![nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)![grafana](https://img.shields.io/badge/Grafana-F2F4F9?style=for-the-badge&logo=grafana&logoColor=orange&labelColor=F2F4F9)![json](https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white)![web](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)


## Nginx Exporrtetr Docker Command

docker run -d --name nginx-exporter --restart unless-stopped   --network host   nginx/nginx-prometheus-exporter:latest   -nginx.scrape-uri http://127.0.0.1/stub_status

