# java-cli-bazel-postgres-data-type--json

## Description
Creates a small table `dog` that uses
a json data type.

## Tech stack
- java
- bazel
  - log4j
  - postgres driver

## Docker stack
- l.gcr.io/google/bazel:latest
- postgresql:alpine

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
