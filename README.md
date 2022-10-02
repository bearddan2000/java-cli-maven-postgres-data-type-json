# java-cli-maven-postgres-data-type-json

## Description
Creates a small table `dog` that uses
a json data type.

## Tech stack
- java
- maven
  - log4j
  - postgres driver

## Docker stack
- maven:3-openjdk-17
- postgres

## To run
`sudo ./install.sh -u`
Creates java-srv/log

## To stop
`sudo ./install.sh -d`
Removes java-srv/log

## For help
`sudo ./install.sh -h`

## Credit
[JSON data type info](https://www.postgresqltutorial.com/postgresql-tutorial/postgresql-json/)
