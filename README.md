# E-Commerce Web Application

A full-stack E-Commerce Web Application built using Java, Spring Boot, MySQL, HTML, CSS, and JavaScript. The application allows users to browse products, manage shopping carts, place orders, and securely interact with the platform through RESTful APIs.

## Features

- User Registration & Login
- Product Browsing
- Product Search
- Shopping Cart Management
- Order Placement
- Product Management
- RESTful API Architecture
- Responsive User Interface
- MySQL Database Integration

## Tech Stack

### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Maven

### Frontend
- HTML
- CSS
- JavaScript

### Database
- MySQL

### Tools
- Git
- GitHub
- Postman
- IntelliJ IDEA
- VS Code

## System Architecture

User → Frontend (HTML/CSS/JS) → Spring Boot REST APIs → MySQL Database

## Key Functionalities

### User Management
- User Registration
- User Login
- Profile Management

### Product Management
- View Products
- Search Products
- Product Details Page
- Add New Products
- Update Product Information
- Delete Products

### Shopping Cart
- Add Items to Cart
- Remove Items from Cart
- Update Item Quantity
- View Cart Summary

### Order Management
- Place Orders
- View Order History
- Manage Orders

## Project Structure

```
E-Commerce-Application
│
├── src/main/java
│   ├── controller
│   ├── service
│   ├── repository
│   ├── entity
│   ├── dto
│   └── config
│
├── src/main/resources
│   └── application.properties
│
├── frontend
│   ├── html
│   ├── css
│   └── javascript
│
└── database
```

## REST API Endpoints

### Products

| Method | Endpoint | Description |
|----------|----------|-------------|
| GET | /api/products | Get all products |
| GET | /api/products/{id} | Get product by ID |
| POST | /api/products | Add product |
| PUT | /api/products/{id} | Update product |
| DELETE | /api/products/{id} | Delete product |

### Cart

| Method | Endpoint | Description |
|----------|----------|-------------|
| POST | /api/cart/add | Add item to cart |
| DELETE | /api/cart/remove/{id} | Remove item from cart |
| GET | /api/cart | View cart |

### Orders

| Method | Endpoint | Description |
|----------|----------|-------------|
| POST | /api/orders | Place order |
| GET | /api/orders | View orders |

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/ecommerce-web-application.git
```

### Backend Setup

```bash
mvn clean install

mvn spring-boot:run
```

### Database Setup

Create a MySQL database:

```sql
CREATE DATABASE ecommerce_db;
```

Update application.properties:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=your_password
```

### Run Application

```bash
mvn spring-boot:run
```

Application will start on:

```bash
http://localhost:8080
```

## Testing APIs

Use Postman to test:

- Product APIs
- Cart APIs
- Order APIs
- User APIs

## Future Enhancements

- JWT Authentication
- Spring Security
- Payment Gateway Integration
- Product Reviews & Ratings
- Wishlist Functionality
- Admin Dashboard
- Email Notifications
- Docker Deployment
- AWS Deployment

## Learning Outcomes

This project helped me gain practical experience in:

- Java Programming
- Spring Boot Development
- REST API Development
- Spring Data JPA
- MySQL Database Design
- MVC Architecture
- CRUD Operations
- API Testing using Postman
- Git & GitHub Version Control

## Author

**Farman Gour**
