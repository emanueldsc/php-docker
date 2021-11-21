# Ambiente de desenvolvimento php com Docker

para subir a aplicação:

```
docker-compose up

docker-compose up --build
```

# Para usar o mysql pelo terminal

Abre o terminal e execute o comando

```
docker exec -it <id_do_container_mysql> bash
```

A senha de acesso do mysql é a mesma senha fornecida no arquivo **docker-compose.yml**, na variável **MYSQL_ROOT_PASSWORD**
