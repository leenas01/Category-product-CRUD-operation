# Category and Product Management API

This project is a Spring Boot application designed to manage categories and products with a one-to-many relationship. The application provides RESTful API endpoints for CRUD operations on both categories and products, with server-side pagination and validation.

## Features

- **Category Management**: Create, read, update, and delete categories.
- **Product Management**: Create, read, update, and delete products.
- **One-to-Many Relationship**: Each category can have multiple products associated with it.
- **Server-Side Pagination**: Pagination support for fetching categories and products.
- **Exception Handling**: Global exception handling using `@ControllerAdvice`.

## Technologies Used

- **Java 8+**
- **Spring Boot**
- **Spring Data JPA**
- **Hibernate**
- **MySQL**
- **Maven**

## Requirements

- **Java 8+**
- **Maven**
- **MySQL**
****

API Endpoints
Category Endpoints
GET /api/categories?page={page}: Get all categories with pagination.
POST /api/categories: Create a new category.
GET /api/categories/{id}: Get a category by ID.
PUT /api/categories/{id}: Update a category by ID.
DELETE /api/categories/{id}: Delete a category by ID.
Product Endpoints
GET /api/products?page={page}: Get all products with pagination.
POST /api/products: Create a new product.
GET /api/products/{id}: Get a product by ID (with associated category details).
PUT /api/products/{id}: Update a product by ID.
DELETE /api/products/{id}: Delete a product by ID.
