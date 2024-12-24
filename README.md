# docker-nginx
Dockerized Nginx checked in local on 2024.12

- Get started with compose
```
docker compose down
docker compose up -d
```

- Copy config from base container and edit with sudo or create another file
```
sudo docker cp nginx-mac:/etc/nginx/nginx.conf ./nginx.conf
```