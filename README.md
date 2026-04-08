# Hogwarts Artifacts Online - Spring Boot Application

A Spring Boot back-end application built while following the "Learn Spring Boot 3" course on YouTube.
This project demonstrates best practices in Spring Boot development, including REST APIs, TDD, CI/CD, and more.

## About

*Hogwarts Artifacts Online* is a sample back-end application developed progressively across multiple branches.
Each branch corresponds to a new feature or concept introduced in the course.

## What's Covered

- **Dependency Injection** and Spring Framework's core container
- **Spring MVC** for building the web layer
- **Spring Data JPA** for data persistence
- **Spring Security** with JWT authentication and authorization
- **Spring Cloud Azure** for cloud deployment
- **Spring Boot Actuator** for monitoring
- **RestClient** for OpenAI API integration
- Paging, sorting, and dynamic queries with JPA Specifications
- **CI/CD** with GitHub Actions
- Test-Driven Development (TDD)

## Run Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Abdifatah2023/hogwarts-artifacts-online.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd hogwarts-artifacts-online
   ```

3. **Launch Redis** (used for caching):

   ```bash
   docker run -d -p 6379:6379 redis
   ```

4. **Run the application:**

   ```bash
   ./mvnw spring-boot:run
   ```

   Or on Windows:

   ```bash
   .\mvnw.cmd spring-boot:run
   ```

## Database

Uses an in-memory H2 database by default. H2 console available at `http://localhost/h2-console` with JDBC URL `jdbc:h2:mem:hogwarts`.

## License

Released under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
