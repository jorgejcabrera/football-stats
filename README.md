
## Overview
API Rest for Cassandra access.

## Requirements
- Java
- Maven
- Cassandra

## Developing application locally
Create and run Pgsql Db and Rabbit Queue:
``` 
$ docker-compose up
```
run server by console with
```
$ mvn spring-boot:run
```
## Cassandra
Start cassandra console
```
$ cqlsh
```

Select the name of the database that you are using
```
$ use <key_space>
```
Describe all tables
```
$ describe tables
```