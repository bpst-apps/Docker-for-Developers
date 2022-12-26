# Docker for Full Stack Application

## Docker Commands

### build full stack app image
```
docker-compose build
```

### run full stack application
Here we are follow the order to run our app components
order: mongo > app > client
```
docker-compose up -d mongo
docker-compose up -d app
docker-compose up -d client
```


### stop full stack application container
```
docker-compose stop
```
