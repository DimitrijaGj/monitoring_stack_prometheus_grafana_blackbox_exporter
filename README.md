# Monitoring web site with Prometheus Black Box Exporter and NGINX Exporter 


## Nginx Exporrtetr Docker Command

docker run -d --name nginx-exporter --restart unless-stopped   --network host   nginx/nginx-prometheus-exporter:latest   -nginx.scrape-uri http://127.0.0.1/stub_status

