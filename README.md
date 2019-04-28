# quarkus-example
Example of microprofile using [Quarkus](https://quarkus.io/)

## Developing 

- Maven
```shell
./mvnw compile quarkus:dev
```

- Docker
```shell
docker build -f src/main/docker/Dockerfile -t quarkus/quarkus-example .

docker run -i --rm -p 8080:8080 quarkus/quarkus-example                
```
