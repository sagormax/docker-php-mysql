# docker-php-mysql
PHP 8.2 &amp; MySQL docker comtainer 

## Clone:
```
git clone git@github.com:sagormax/docker-php-mysql.git
```

## Setup and run from root directory:
```
docker-compose up -d
```

## Run command on inside APP Server:
```
docker exec -it app-server bash
```

## APP Server (All project files will goes to inside /src folder):
http://localhost:8082

## phpmyadmin:
http://localhost:8081
```
DB: my_db
USER: my_db
PASSWORD: my_db
```

## Mysql server EXPOSE PORT:
```
HOST: localhost
PORT: 3307
MYSQL_ROOT_PASSWORD=root
MYSQL_DATABASE=my_db
MYSQL_USER=my_db
MYSQL_PASSWORD=my_db