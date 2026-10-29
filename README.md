# Bookstore API

## Technologies
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Spring Security
- JWT
- Swagger

## Run
1. MySQL database `bookstore` तयार करा.
2. `application.properties` मध्ये database details द्या.
3. Spring Boot application run करा.

## Swagger
http://localhost:8080/swagger-ui/index.html

## Main APIs
- POST /api/users/register
- POST /api/users/login
- GET /api/books
- POST /api/books
- PUT /api/books/{id}
- DELETE /api/books/{id}
- GET /api/books/search?keyword=Java
- POST /api/orders
- GET /api/orders
- PUT /api/orders/{id}/status?status=SHIPPED