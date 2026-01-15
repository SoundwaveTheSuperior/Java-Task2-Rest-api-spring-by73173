# First REST API – Spring Boot

This project is a simple REST API built with **Spring Boot** as part of Java & Spring Framework coursework.  
It demonstrates basic REST principles such as request handling, response mapping, service layers, and exception handling.

---

## Technologies Used

- Java
- Spring Boot
- Spring Web
- Maven
- Swagger (OpenAPI)
- Postman (for testing)

---

## Project Structure



src/main/java/pl/edu/vistula/first_rest_api_spring
│
├── product
│   ├── api
│   │   ├── ProductController
│   │   ├── request
│   │   │   └── ProductRequest
│   │   └── response
│   │       └── ProductResponse
│   │
│   ├── domain
│   │   └── Product
│   │
│   ├── repository
│   │   └── ProductRepository
│   │
│   ├── service
│   │   └── ProductService
│   │
│   └── support
│       ├── ProductMapper
│       └── exception
│           ├── ProductNotFoundException
│           ├── ProductExceptionSupplier
│           └── ProductExceptionAdvisor
