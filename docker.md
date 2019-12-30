# Docker

En el terminal:

* Instalar y correr contenedor:

```text
docker-compose up
```

* correr contenedor sin detalle del terminal:

```text
docker-compose up -d
```

* Muestra los contenedores que están corriendo:

```text
docker ps
```

* Detener contenedor:

```text
docker-compose stop
```

Archivo "docker-compose.yml" archivo de configuración que genera el contenedor

Remover contenedor

```text
docker-compose down --volumes
```

**stop all containers:**  
`docker kill $(docker ps -q)`

**remove all containers**  
`docker rm $(docker ps -a -q)`

**remove all docker images**  
`docker rmi $(docker images -q)`

Delete all

docker system prune

[https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes](https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes)
