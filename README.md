# Docker LAMP Latest

PHP = 7.4.14-apache
MySQL = 8.0.22
PHPMyAdmin = 5.0.4

```
docker-compose up --build
docker-compose up -d

docker-compose ps
ip
docker-compose down

docker build . -t my-app-image:1.0.1
```

http://localhost:5000/
http://localhost:8080/

mysql-data volume
docker volume ls

docker volume rm lamp_mysql-data
