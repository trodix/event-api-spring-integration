# Alfresco Java Event API - Spring Integration - Using Spring Boot Parent

Sample application to demonstrate the pure Spring Integration approach to use the Alfresco Java Event API.

It is a Spring Boot application that makes use of the [Alfresco Java Event API Spring Boot Starter](../../alfresco-java-event-api/README.md#spring-boot-custom-starter)
to define sample Spring Integration flows that log information about specific handled events.

## Usage

### Pre-Requisites

To properly build and run the project in a local environment it is required to have installed some tools.

* Java 17:
```bash
$ java -version

openjdk version "17.0.4" 2022-07-19 LTS
OpenJDK Runtime Environment (build 17.0.4+8-LTS)
OpenJDK 64-Bit Server VM (build 17.0.4+8-LTS, mixed mode, sharing)

```

* [Maven](https://maven.apache.org/install.html) version 3.3 or higher:
```bash
$ mvn -version

Apache Maven 3.6.1 (d66c9c0b3152b2e69ee9bac180bb8fcc8e6af555; 2019-04-04T21:00:29+02:00)
```

* [Docker](https://docs.docker.com/install/) version 1.12 or higher:
```bash
$ docker -v

Docker version 20.10.2, build 2291f61
```

* [Docker compose](https://docs.docker.com/compose/install/):
```bash
$ docker compose version

Docker Compose version v2.28.1-desktop.1
```

### Build and run

```bash
$ docker compose up -d
```

### Go to Alfresco

http://localhost:8080/share
