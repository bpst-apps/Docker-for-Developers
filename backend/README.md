# node-mongo-docker
A node and express docker template with Mongo

## Docker Commands

### build image from docker compose
```
docker compose build
```

### run mongo container
```
docker-compose up -d mongo
```

### run app container
```
docker-compose up -d app
```

### check logs of container
```
docker logs <container id>
eg: docker logs 9b7650bbc9a0
```

### stop all running containers
```
docker-compose stop
```

