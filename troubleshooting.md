## Troubleshooting 502 Bad Gateway

1. Check if Flask app is running on the expected port (5000)
2. Check NGINX/ALB configuration – target IP and port must be correct
3. Check logs for app crash: `docker logs <container_id>`
