# Simple website

### Start and stop docker services

`cd SimpleWebsite/docker/`

Start:
`docker-compose up -d`

Stop:
`docker-compose down`

### Docker configuration

- Web Server: **nginx:stable-alpine**
- Database: **mariadb:latest** and **phpmyadmin:latest**
- Server Lang: **php:8.0.6-fpm-alpine** with **pdo** and **pdo_mysql**
