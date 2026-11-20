# Employee Management — Module 1

Mini project for **Module 1: Getting Started with Spring Boot**. This starter application demonstrates a Spring Boot project structure and a working Hello World REST endpoint at `/hello`.

## Requirements

- JDK 17+
- Maven 3.6+ (or use the Maven wrapper if you add one locally)

## Run the application

```bash
mvn spring-boot:run
```

The app starts at `http://localhost:8080`.

## Test the API

```bash
curl http://localhost:8080/hello
```

Expected response:

```text
Hello, Employee Management!
```

## Project structure

```text
src/main/java/com/example/employeemanagement/
├── EmployeeManagementApplication.java  # Spring Boot entry point and auto-configuration
└── HelloController.java                # REST endpoint
src/main/resources/application.properties
pom.xml
```

## Concepts covered

- `spring-boot-starter-web` brings in Spring MVC and an embedded web server.
- `@SpringBootApplication` enables component scanning and Spring Boot auto-configuration.
- `@RestController` and `@GetMapping` expose the `/hello` HTTP endpoint.
