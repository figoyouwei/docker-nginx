# docker-nginx
Dockerized Nginx checked in local on 2024.12.23

- Get started with compose
```
docker compose up -d
```

- Copy config from base container and edit with sudo or create another file
```
sudo docker cp nginx-base:/etc/nginx/nginx.conf ./nginx.conf
```

- Put it back to nginx-base container
```
sudo docker cp ./default.conf nginx-base:/etc/nginx/conf.d/default.conf
```

- Test nginx-base container
```
sudo docker exec nginx-base nginx -t
```

- Restart nginx-base container
```
sudo docker exec nginx-base nginx -s reload
```