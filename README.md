# docker-nginx
Dockerized Nginx checked in local on 2024.12

- Get started with compose default
```
docker compose down
docker compose up -d
```

- Get started with compose custom
```
docker compose -f compose-hk220.yml down
docker compose -f compose-hk220.yml up -d
```

- Copy config from base container and edit with sudo or create another file
```
sudo docker cp nginx-mac:/etc/nginx/nginx.conf ./nginx.conf
```