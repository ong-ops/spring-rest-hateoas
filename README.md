## Spring Rest Service with HATEOAS Guide

Create a Spring rest service with HATEOAS (Hypermedia as the engine on application state).

https://spring.io/guides/gs/rest-hateoas

---

## Run the Service

### Gradle

#### Run application

```sh
./gradlew bootRun
```

#### Alternative - Build JAR file

```sh
./gradlew build
```

```sh
java -jar build/libs/spring-rest-hateoas-0.0.1-SNAPSHOT.jar
```

### Maven

#### Run application

```
./mvnw spring-boot:run
```

#### Alternative - Build JAR file

```
./mvnw clean package
```

```
java -jar target/spring-rest-hateoas-0.0.1-SNAPSHOT.jar
```