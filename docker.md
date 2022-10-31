## Build and start docker containers
* Build docker images
``` bash
docker-compose build --no-cache
```
* Start docker containers
``` bash
docker-compose up --force-recreate
```

## Stop docker containers
* Remove all containers and images
``` bash
docker system prune -a
```
* Kill all runing containers
``` bash
docker container kill $(docker ps -q)
```
