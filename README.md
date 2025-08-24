# Employee Management API

This project is a RESTful API built to perform basic CRUD (Create, Read, Update, Delete) operations for an employee management system. It's developed using **Spring Boot** and Java.

## Technologies Used

* **Java 17**: The core programming language for the project.
* **Spring Boot**: The main framework used for building the API.
* **Spring Data JPA**: The layer used for handling database operations.
* **Hibernate**: The JPA implementation that provides Object-Relational Mapping (ORM).
* **H2 Database**: An in-memory database used for development purposes.
* **Maven**: The build automation tool for managing project dependencies.
* **Lombok**: A library used to reduce boilerplate code.

## Features

The API provides the following endpoints:

* **`POST /api/employees`**: Creates a new employee.
* **`GET /api/employees`**: Retrieves a list of all employees.
* **`GET /api/employees/{id}`**: Retrieves a specific employee by ID.
* **`PUT /api/employees/{id}`**: Updates the information of an employee by ID.
* **`DELETE /api/employees/{id}`**: Deletes an employee by ID.

## How to Run Locally

To run the project on your local machine, follow these steps:

1.  Clone the repository: `git clone https://github.com/YOUR_USERNAME/employee-management.git`
2.  Navigate to the project directory: `cd employee-management`
3.  Open the main class file (`EmployeeManagementApplication.java`) in VS Code.
4.  Click the "Run" button to start the application.

The application will run on `http://localhost:8080` by default.

## How to Test the API

You can use a tool like Postman to test the API endpoints.

**Example POST Request:**

`POST http://localhost:8080/api/employees`

**Body (JSON):**
```json
{
    "firstName": "Ahmet",
    "lastName": "Yilmaz",
    "email": "ahmet.yilmaz@example.com"
}