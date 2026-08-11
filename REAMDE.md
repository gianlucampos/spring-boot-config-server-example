# Spring Boot Config Server

Simple test application for validating:

* Spring Cloud Config Server
* Git-based configuration
* Spring Boot Actuator

The application retrieves configuration from a private Git repository and exposes it through the Config Server API.

### Test endpoint

```bash
curl http://localhost:8080/kafka-migration/default/develop
or
curl http://localhost:8080/kafka-migration/default/master
```
