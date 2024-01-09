# desafio-docker

## PostgreSQL
```
docker container run --name postgresdb -e POSTGRES_USER=docker_usr -e POSTGRES_PASSWORD=docker_pwd -e POSTGRES_DB=curso_docker -p 5432:5432 -d postgres
```
## MySQL
```
docker container run --name mysqldb -e MYSQL_ROOT_PASSWORD=root -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd -e MYSQL_DATABASE=docker_db -p 3306:3306 -d mysql
```
## MongoDB
```
docker container run --name mongodb -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd -p 27017:27017 -d mongo
```
