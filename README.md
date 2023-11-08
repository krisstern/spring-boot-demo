# README

This is a simple Spring Boot demo application. 

## To run
```shell
./mvnw spring-boot:run
```

## To test
```shell
./mvnw verify
```

Or
```shell
./mvnw test
```

## In the browser
The application is available at http://localhost:8080. 

## Check the health of the application
Run the following:
```shell
curl localhost:8080/actuator/health
```

Invoke shutdown through curl:
```shell
curl -X POST localhost:8080/actuator/shutdown
```
