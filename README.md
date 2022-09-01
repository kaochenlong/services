# Dockerized Services

1. Execute `./run` command will launch a menu to pick service you want.
2. `volumes` folder will be created automatically and will be mounted into containers.

- MongoDB
  - hostname: `mongodb`
  - username: `mango`
  - password: `juice`
- PostgreSQL
  - hostname: `postgresql`
  - username: `postgres`
  - password: `postgres`
  - port: 5432
- MySQL
  - hostname: `mysql`
  - root password: `helloworld`
  - port: 3306
- Redis
  - hostname: `redis`
  - port: 6379
- ElasticSearch
  - hostname: `elasticsearch`
  - port: 9200
- Adminer
  - port: 8080

You can modify all those username, password and port by editing the `.env` file.

by eddie@5xcampus.com
