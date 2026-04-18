# DevinAi

A minimal Spring Boot service.

## Requirements

- Java 17+
- Maven 3.6.3+

## Run

```bash
mvn spring-boot:run
```

## Endpoints

| Method | Path   | Response |
| ------ | ------ | -------- |
| GET    | /ping  | `pong`   |

```bash
curl http://localhost:8080/ping
# pong
```

## Test

```bash
mvn test
```
