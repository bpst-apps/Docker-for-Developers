# node-docker
Simple node and express docker 

# Docker Commands

### create docker image using Dockerfile
```
docker build -t <image name> .
eg: docker build -t bpst/simple-backend .
```

### view docker images
```
docker images
```

### remove docker image
```
docker rmi <image id>
eg: docker rmi 12301f222ac7
```

### run container from image
```
docker run -p <port container>:<port application> <image name>
eg: docker run -p 4000:4000 bpst/simple-backend
```

### view running containers
```
docker ps
docker ps --all
```

### stop running container
```
docker stop <running container id>
eg: docker stop 4cf45ce35bfa
```