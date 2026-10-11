# Student Management API

A beginner-friendly REST API built using Java and Spring Boot.

## Features
- View all students
- Find a student by ID
- Add a student
- Delete a student

## Technologies
- Java 21
- Spring Boot
- Maven
- REST API

## Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | /students | Get all students |
| GET | /students/{id} | Get student by ID |
| POST | /students | Add a student |
| DELETE | /students/{id} | Delete a student |

## Run Locally

mvn spring-boot:run

The application runs at http://localhost:8080.

## Note
This project uses in-memory storage. Data resets when the application restarts.
