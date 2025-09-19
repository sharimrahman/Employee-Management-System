Employee Management System

A Spring Boot application providing CRUD operations for managing employees and departments with MySQL database integration. APIs can be tested via Postman.

Features

Manage Employees and Departments: Create, Read, Update, Delete, and Patch records.

Relationships maintained: Employee references Department via foreign key.

RESTful APIs for all operations (GET, POST, PUT, PATCH, DELETE).

Technology Stack 

Backend: Java, Spring Boot

Database: MySQL

API Testing: Postman

IDE & Tools: Eclipse

How to Run

Configure application.properties with your MySQL DB credentials.

Run DBScript to create database/tables or use spring.jpa.hibernate.ddl-auto=update.

Run Application class from Eclipse.

Test APIs at http://localhost:8080/employees and http://localhost:8080/departments.

Future Enhancements

Add User Accounts for employees with login credentials.

Implement Admin System for centralized management of employees and departments.
