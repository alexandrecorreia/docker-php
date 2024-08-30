# Docker e PHP

Levantando containers com diferentes versões do PHP

# Atualizando o docker-compose
curl -SL https://github.com/docker/compose/releases/download/v2.29.1/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose

# Rodando o container
docker-compose up -d

# Containers PHP-APACHE

| IMAGEM         | PORTAS                              | NAMES SERVER         |
| :------------- | :---------------------------------- | :--------------------|
| php:5.5-apache | 0.0.0.0:8080->80/tcp :::8080->80/tcp| app1.apache          |
| php:7.4-apache | 0.0.0.0:8081->80/tcp :::8081->80/tcp| app2.apache          |

# Containers PHP-FPM - NGINX

| IMAGEM             | PORTAS                               | NAMES SERVER    |
| :----------------- | :----------------------------------- | :---------------|
| nginx:alpine       | 0.0.0.0:8082->80/tcp :::8082->80/tcp |   app3.nginx    |
| nginx:alpine       | 0.0.0.0:8083->80/tcp :::8083->80/tcp |   app4.nginx    |
| php:5.5.38-fpm     | 9000/tcp                             |   app3.files    |
| php:5.6-fpm-alpine | 9000/tcp                             |   app4.files    |

## Autor

- [@alexandrecorreia](https://github.com/alexandrecorreia/docker-php)

