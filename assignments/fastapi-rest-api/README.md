# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build and test RESTful APIs using the FastAPI framework in Python. Practice designing endpoints, handling requests and responses, and working with data models.

## 📝 Tasks

### 🛠️ Create a Simple API Endpoint

#### Description
Build a FastAPI application with a single endpoint that returns a welcome message in JSON format.

#### Requirements
Completed program should:

- Use FastAPI to create an app
- Implement a GET endpoint `/welcome` that returns `{ "message": "Welcome to FastAPI!" }`
- Run the server locally and test the endpoint

### 🛠️ Design a CRUD API for a Resource

#### Description
Extend your FastAPI app to manage a list of books. Implement endpoints to create, read, update, and delete books.

#### Requirements
Completed program should:

- Define a `Book` data model with fields: `id`, `title`, and `author`
- Implement endpoints:
  - `GET /books` (list all books)
  - `POST /books` (add a new book)
  - `GET /books/{id}` (get a book by id)
  - `PUT /books/{id}` (update a book)
  - `DELETE /books/{id}` (remove a book)
- Store books in an in-memory list (no database required)
- Return appropriate status codes and error messages
