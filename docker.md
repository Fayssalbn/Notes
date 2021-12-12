# Docker

## Docker-compose

```
docker-compose up
```

  Apply executable permissions to the binary :

```
sudo chmod +x /usr/local/bin/docker-compose
```

# Container

```
docker container ls --all
```

 ```
 docker inspect -f '{{.Name}} - {{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' $(docker ps -aq)
 ```

# image

docker remove image

```
docker image rm
```
