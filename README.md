# java-cli-sbt-postgres-data-type-json

## Description
Creates a small table `dog` that uses
a json data type.

## Tech stack
- java
- sbt
  - log4j
  - postgres driver

## Docker stack
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10
- postgres:alpine

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
