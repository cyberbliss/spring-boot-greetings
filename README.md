# Greetings
A test Spring Boot application which exposes various REST endpoints.

## Usage
App listens on port 8080.
Endpoints:
- /greeting?name=foobar
- /actuator/health

## Development
Use spring-boot:run to run app locally.
Use job:build to build app's Docker image and push to gcr.io repo.