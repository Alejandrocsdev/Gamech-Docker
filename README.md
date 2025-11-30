# Gamech

### Start containers (Build image if missing)

```
docker-compose -f docker-compose.dev.yml up -d
```

### Rebuild images and start containers:

```
docker-compose -f docker-compose.dev.yml up -d --build
```

### Stop containers:

```
docker compose -f docker-compose.dev.yml stop
```

### Remove containers, networks, and volumes:

```
docker-compose -f docker-compose.dev.yml down
```
