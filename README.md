# 🛍️ E-Commerce Application

Welcome to the E-Commerce Application! This project provides the backend services for an online store where users can browse products, manage their carts, and place orders securely.

## 📖 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Database Schema](#database-schema)
- [Getting Started](#getting-started)
- [API Documentation](#api-documentation)
- [Screenshots](#screenshots)
- [Acknowledgements](#acknowledgements)

## 📚 About the Project

The E-Commerce Application is a backend system developed using Java and Spring Boot. It is designed to handle core e-commerce functionalities, including user authentication, product catalog, order processing, and payment management.

## ✨ Features

### User Features:
- User registration and login with JWT authentication.
- Browse products by category, price, and rating.
- Add/remove products to/from the cart.
- Place orders and view order history.

### Admin Features:
- Add, update, or delete products.
- Manage inventory and product availability.
- View and update order statuses.

### Other Highlights:
- Secure authentication and authorization with Spring Security.
- RESTful APIs for seamless frontend integration.
- Swagger integration for API documentation.

## 💻 Tech Stack

- **Programming Language**: Java
- **Frameworks**: Spring Boot, Spring Security
- **Database**: MySQL
- **Tools**: Maven, Swagger
- **Testing**: JUnit, Mockito

## 🗂️ Database Schema

The application uses MySQL as the database to store product and order information.

### Example Tables:
- **Users**: Stores user details like name, email, and password.
- **Products**: Contains details of the products available in the store, such as name, description, price, and stock quantity.
- **Orders**: Tracks user orders including order status and related products.
- **Carts**: Stores the products added to a user's cart before placing an order.

## 🚀 Getting Started

### Prerequisites:
- Java 8 or higher
- MySQL Database
- Maven or Gradle
