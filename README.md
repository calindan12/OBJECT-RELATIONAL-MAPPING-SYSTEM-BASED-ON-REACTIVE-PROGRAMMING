# Reactive Object-Relational Mapping System

A backend application developed as part of a Bachelor's Thesis that demonstrates the implementation of a reactive object-relational mapping system using Spring WebFlux and Spring Data R2DBC.

The project compares the performance of reactive and blocking approaches for database access through concurrent request processing and provides a web interface for benchmarking and visualization.

---

## Technologies

- Java 21
- Spring Boot
- Spring WebFlux
- Spring Data R2DBC
- Spring JDBC (Blocking implementation)
- MySQL
- Thymeleaf
- Bootstrap 5
- Chart.js
- Maven

---

## Features

- Reactive CRUD operations
- Non-blocking database access
- Blocking implementation using JdbcTemplate
- Concurrent request processing
- Reactive vs Blocking performance benchmark
- Web dashboard built with Thymeleaf
- Performance visualization using Chart.js

---

## Project Structure

```
src
├── controller
├── repository
├── model
├── DTO
├── templates
└── resources
```

---

## Architecture

```
Client
    │
    ▼
Spring WebFlux Controllers
    │
    ▼
Reactive Repositories (R2DBC)
    │
    ▼
MySQL Database
```

For comparison, the project also includes a blocking implementation based on Spring JDBC (JdbcTemplate).

---

## Performance Benchmark

The application includes a benchmarking page that compares reactive and blocking endpoints by executing multiple concurrent HTTP requests.

The benchmark displays:

- execution time
- performance gain
- comparison chart
- benchmark statistics

---

## Screenshots

### Dashboard

_Add a screenshot here._

### Benchmark

_Add a screenshot here._

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/reactive-orm.git
```

### Build the project

```bash
mvn clean install
```

### Run the application

```bash
mvn spring-boot:run
```

Open:

```
http://localhost:8080
```

---

