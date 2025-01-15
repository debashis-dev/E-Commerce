🛍️ E-Commerce Application

Welcome to the E-Commerce Application! This project provides the backend services for an online store where users can browse products, manage their carts, and place orders securely.

📖 Table of Contents

About the Project

Features

Tech Stack

Database Schema

Getting Started

API Documentation

Screenshots

Contributing

License

📚 About the Project

The E-Commerce Application is a backend system developed using Java and Spring Boot. It is designed to handle core e-commerce functionalities, including user authentication, product catalog, order processing, and payment management.

✨ Features

User Features:

User registration and login with JWT authentication.

Browse products by category, price, and rating.

Add/remove products to/from the cart.

Place orders and view order history.

Admin Features:

Add, update, or delete products.

Manage inventory and product availability.

View and update order statuses.

Other Highlights:

Secure authentication and authorization with Spring Security.

RESTful APIs for seamless frontend integration.

Swagger integration for API documentation.

💻 Tech Stack

Programming Language: Java

Frameworks: Spring Boot, Spring Security

Database: MySQL/PostgreSQL

Tools: Maven, Swagger

Testing: JUnit, Mockito

Deployment: Docker, AWS/Heroku

🗃️ Database Schema

Users Table:

Column

Type

Description

id

INT

Primary Key

name

VARCHAR

User's full name

email

VARCHAR

User's email address

password

VARCHAR

Encrypted password

role

ENUM

User or Admin

Products Table:

Column

Type

Description

id

INT

Primary Key

name

VARCHAR

Product name

description

TEXT

Product details

price

DECIMAL

Product price

stock

INT

Quantity available

Orders Table:

Column

Type

Description

id

INT

Primary Key

user_id

INT

Linked to Users

total_price

DECIMAL

Total order amount

order_date

TIMESTAMP

Date of order

status

ENUM

Order status

🚀 Getting Started

Prerequisites

Java 17+

Maven

MySQL

Docker (optional for deployment)

Installation

Clone the repository:

git clone https://github.com/your-username/ecommerce-backend.git

Navigate to the project directory:

cd ecommerce-backend

Install dependencies:

mvn clean install

Set up the database:

Update application.properties with your database credentials.

Run the SQL script located in the /resources folder to initialize the database.

Start the application:

mvn spring-boot:run

📘 API Documentation

API documentation is available via Swagger UI. Once the application is running, you can access it at:

http://localhost:8080/swagger-ui/index.html

📸 Screenshots

Swagger API Documentation:



Database Schema:



🤝 Contributing

Contributions are welcome! Follow these steps:

Fork the repository.

Create a new branch:

git checkout -b feature/YourFeatureName

Commit your changes:

git commit -m 'Add some feature'

Push to the branch:

git push origin feature/YourFeatureName

Open a Pull Request.

📜 License

This project is licensed under the MIT License.

🙌 Acknowledgements

Spring Boot Documentation

Swagger UI Documentation

OpenAPI Initiative
