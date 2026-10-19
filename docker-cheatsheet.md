# Docker Cheatsheet

## Containers
```
docker run -d --name <n> <image>
docker ps / docker ps -a
docker stop/start/restart <n>
docker logs <n> / docker exec -it <n> bash
docker rm <n>
```

## Images
```
docker build -t <tag> .
docker images / docker rmi <image>
docker pull/push <image>
```

## Compose
```
docker-compose up -d
docker-compose down
docker-compose logs
```

## Cleanup
```
docker system prune -a
docker volume prune
```
