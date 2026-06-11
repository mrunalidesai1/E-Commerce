# E-Commerce Web Application

## Project Overview

This is a Full Stack E-Commerce Web Application developed using Angular, Spring Boot, and MySQL. The application allows users to browse products, add products to cart, place orders, and manage their shopping experience. Admin users can manage products and monitor orders.

## Technologies Used

### Frontend

* Angular
* TypeScript
* HTML
* CSS
* Bootstrap

### Backend

* Java 17
* Spring Boot
* Spring Data JPA
* Spring Security
* REST API

### Database

* MySQL

## Features

### User Features

* User Registration
* User Login
* Product Listing
* Product Search
* Add to Cart
* Remove from Cart
* Place Orders
* Order History

### Admin Features

* Add Products
* Update Products
* Delete Products
* View Orders
* Manage Products

## Project Structure

E-Commerce

├── frontend

├── backend

├── README.md

└── .gitignore

## Database Configuration

Create a database in MySQL:

CREATE DATABASE ecommercenew_db;

Update database credentials in:

backend/src/main/resources/application.properties

Example:

spring.datasource.url=jdbc:mysql://localhost:3306/ecommercenew_db

spring.datasource.username=root

spring.datasource.password=your_password

## Running the Backend

Navigate to backend folder:

cd backend

Run:

mvn spring-boot:run

Backend URL:

http://localhost:8082

## Running the Frontend

Navigate to frontend folder:

cd frontend

Install dependencies:

npm install

Run Angular application:

ng serve

Frontend URL:

http://localhost:4200

## API Endpoints

Authentication

* POST /api/auth/register
* POST /api/auth/login

Products

* GET /api/products
* GET /api/products/{id}
* POST /api/products
* PUT /api/products/{id}
* DELETE /api/products/{id}

Cart

* GET /api/cart
* POST /api/cart/add

Orders

* POST /api/orders
* GET /api/orders

## Author

Mrunali Desai

Java Full Stack Developer

Skills:

* Java
* Spring Boot
* Angular
* React.js
* MySQL
* REST APIs
* HTML, CSS, JavaScript
