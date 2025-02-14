# Atipera recruitment task

Atipera recruitment task for the position of Junior Java Developer.

# Application
`Spring Boot` web application that exposes REST API to retrieve information about `Github` user's repositories which are not forks.

# Endpoints
`GET /api/repos/{username}`

# Information

- Java 21
- Spring Boot 3
- WebClient for making HTTP requests to the Github API
- WireMock for testing the application

# Running the Application

1. Ensure you have Java 21 installed on your machine.

2. Clone the repository.

3. Navigate to the project directory.

4. Run the application using the command: `./mvnw spring-boot:run`

# Testing

To run the tests, use the command: `./mvnw test`
