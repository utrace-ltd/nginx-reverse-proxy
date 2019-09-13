# nginx-reverse-proxy
Docker image for nginx reverse proxy

## Usage
```bash
docker run -e VH_example_com="http://s1.example.com" -p 80:80 -p 443:443 -v ./ssl/:/etc/nginx/ssl/ --rm utrace/nginx-reverse-proxy
```
