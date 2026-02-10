# Enterprise Task Management System

A full-stack enterprise-grade task management application designed for internal organizational use.
The system allows authenticated users to create, assign, track, and manage tasks with role-based access control.

This project simulates a real-world production application using modern Java and frontend technologies.

---

## Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Security (JWT-based authentication)
- Spring Data JPA (Hibernate)
- PostgreSQL
- Maven

### Frontend
- React
- Axios
- HTML, CSS, JavaScript

---

## Key Features

- User authentication and authorization using JWT
- Role-based access control (ADMIN, USER)
- Create, update, delete, and track tasks
- RESTful APIs with validation and exception handling
- Pagination and sorting
- Secure backend architecture

---

## Setup Instructions

Backend:
cd backend
mvn clean install
mvn spring-boot:run

Frontend:
cd frontend
npm install
npm start

