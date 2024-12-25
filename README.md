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

- Verify hk220 nginx
```
curl 43.129.80.220
curl www.docker-registry.asia
```
