# docker-php

Docker && Ubuntu 18.04 && Apache2 && Php && Mysqli && Sqlsrv && PhpMyAdmin

## Requirements

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/)

## About this docker's settings

- ubuntu:18.04
- apache2
- php 7.2
- sqlsrv
- mysqli
- nsq

## Before installation

Before installation change this [line](https://github.com/emalherbi/docker-php-7/blob/master/docker-compose.yml#L10).

```yml
volumes:
  - /home/eduardo/Sites/docker/www:/var/www/html
```

## Installation

```bash
docker-compose up -d --build --force-recreate --remove-orphans
```

## Server Root

```
localhost:9086
```

## PhpMyAdmin

```
localhost:9087
```
