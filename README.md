# static-website-docker-nginx
static website with docker &amp; nginx

```
docker build . -t my-client
docker run -it -p 3001:80 -d -v "$(pwd)"/html:/usr/share/nginx/html my-client
```