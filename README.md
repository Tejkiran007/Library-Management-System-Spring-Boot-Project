Library Management System
A simple Spring Boot REST API for managing books and authors.

How It Works
You can add, view, update, and delete authors and books using HTTP requests.

Each book is linked to an author.

All data is stored in an in-memory H2 database (no setup required).

API Endpoints
Author APIs
GET /api/authors – Get all authors

GET /api/authors/{id} – Get author by ID

POST /api/authors – Add a new author

PUT /api/authors/{id} – Update author info

DELETE /api/authors/{id} – Delete an author

Book APIs
GET /api/books – Get all books

GET /api/books/{id} – Get book by ID

GET /api/books/author/{authorId} – Get books by author

POST /api/books – Add a new book



PUT /api/books/{id} – Update book info

DELETE /api/books/{id} – Delete a book

Getting Started
Clone the repository

Run:

text
mvn spring-boot:run
Use Postman to test the API endpoints

Database
Uses H2 in-memory database

Access H2 console at: http://localhost:8080/h2-console


Username: root

Password: Password
