# Student Manager

A Spring Boot web app for managing student records, built with Java, Thymeleaf, Spring Data JPA, and an in-memory H2 database.

## Run locally

Requires Java 21. From this directory, run:

```powershell
.\mvnw.cmd spring-boot:run
```

Open [http://localhost:8081](http://localhost:8081). The H2 console is at [http://localhost:8081/h2-console](http://localhost:8081/h2-console). Use JDBC URL `jdbc:h2:mem:studentdb`, username `sa`, and a blank password. The in-memory database resets when the app stops.
