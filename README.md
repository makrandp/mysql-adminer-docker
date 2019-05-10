# MySql with Docker

### Adminer is used for managing the database

## Setup 
```$xslt
mkdir ~/mysql-data #persistent data
docker-compose up
```

## Useful Commands
```$xslt
docker-compose up
docker-compose stop
docker-compose rm -f
docker-compose down --rmi all
```

## Adminer endpoint 
[http://localhost:8080](http://localhost:8080)

## Adminer Setup
- System: `MySQL`
- Server: `mysql-dev`
- Username: `root`
- Password: `password`
- Database: `demodb` 


