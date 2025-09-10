# Student Management API

A simple **Spring Boot** REST API for managing student records, built with **Java 24**, **Spring Data JPA**, and **MySQL**. This project allows you to perform basic CRUD operations on students.

## Features

- **Create** a new student
- **Read** all students or a specific student by ID
- **Update** student details
- **Delete** a student

## Technology Stack

- Java 24
- Spring Boot 3.5.5
- Spring Data JPA
- MySQL
- Maven

## API Endpoints

| Method | Endpoint                  | Description                  |
|--------|---------------------------|------------------------------|
| GET    | `/students`               | Get all students             |
| GET    | `/students/{id}`          | Get student by ID            |
| POST   | `/students`               | Create a new student         |
| PUT    | `/students/{id}`          | Update a student             |
| DELETE | `/students/{id}`          | Delete a student             |

### Example Request (POST `/students`)

```json
{
    "firstName": "John",
    "lastName": "Doe",
    "email": "john@xyz.com"
}
```

**SETUP INSTRUCTIONS**

1 Clone the repository
git clone https://github.com/Ubaiddar1614/student-management-api.git
cd student-management-api
Configure MySQL:

2 Create a database named university_db

3 Update application.properties with your MySQL username and password

Run the application:

mvn spring-boot:run


The API will be accessible at http://localhost:8080/students.

Future Updates

Pagination and filtering for students

Advanced search capabilities

Integration with frontend applications

JWT authentication and user roles

**License**

This project is licensed under the MIT License. See the LICENSE
 file for details.


