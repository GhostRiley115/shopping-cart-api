# Shopping Cart API (Spring Boot)

RESTful API developed using Java and Spring Boot to simulate a shopping cart system, allowing users to manage orders, products, and checkout operations.

This project follows a layered architecture (Controller → Service → Repository) and represents a backend system similar to food delivery or e-commerce platforms.

## Technologies
- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database
- Swagger (Springfox)
- Gradle

## Features
- Shopping cart creation
- Add items to cart
- Remove items from cart
- Calculate total cart value
- Close/checkout cart
- Relationship between customer, product, and restaurant

## Project Structure
The project is organized using a standard Spring Boot architecture:
- Controller -> Handles HTTP requests
- Service -> Business logic
- Repository -> Data access layer (JPA)
- Entity -> Database models

## Database
- Type: H2 (in memory)
- Automatically created at runtime using Hibernate
- Resets every time the application restarts

## How to run
git clone https://github.com/YOUR_USERNAME/shopping-cart-api.git
cd shopping-cart-api
./gradlew bootRun

Or run directly via your IDE (IntelliJ, Eclipse, etc.)

## Access
- API Base URL: http://localhost:8081
- Swagger UI (API documentation): http://localhost:8081/swagger-ui/
- H2 Console (database access): http://localhost:8081/h2-console

## H2 Database Access
Use the following configuration:
- JDBC URL: jdbc:h2:mem:testdb
- Username: sa
- Password: (leave blank)

## Domain Model
- Customer (Cliente)
- Product (Produto)
- Restaurant (Restaurante)
- Item
- Shopping Cart (Sacola)

## Objective
To practice backend development using Spring Boot, focusing on:
- REST API design
- Layered architecture
- Database relationships
- Business logic implementation

## Project Context
This project represents the backend of a simulated real-world system.

It can be integrated with a frontend (web or mobile) to create a complete application, similar to platforms like food delivery services.

## Future Improvements
- Authentication and authorization (JWT)
- Migration to a real database (PostgreSQL/MySQL)
- Deployment (cloud environment)
- Integration with frontend applications
