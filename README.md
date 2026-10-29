# taskapp

Lightweight Java full-stack app: Spring Boot 3 (Java 17) REST API + static HTML/JS frontend served from the same JAR.

## Run locally
    mvn clean package
    java -jar target/app.jar
Open http://localhost:8080

## Endpoints
- GET    /api/health
- GET    /api/tasks
- POST   /api/tasks     {"title":"..."}
- DELETE /api/tasks/{id}

Container port: 8080. Built JAR: target/app.jar
