# 🚀 Employee Management System

A backend Employee Management System developed using Spring Boot.  
This application provides RESTful APIs to manage employee records with MariaDB database integration, following layered architecture and industry-standard backend practices.

---

## 📌 Project Overview

The Employee Management System (EMS) is designed to perform CRUD operations on employee data.  
It demonstrates real-world backend development concepts including REST API design, database integration, exception handling, and clean architectural separation.

---

## 🛠️ Tech Stack

- Java 17  
- Spring Boot  
- Spring Web  
- Spring Data JPA  
- Hibernate ORM  
- MariaDB  
- Maven  
- Lombok  

---

## ✨ Features

✅ Create new employees  
✅ Retrieve all employees  
✅ Retrieve employee by ID  
✅ Update employee details  
✅ Delete employees  
✅ Global exception handling  
✅ Clean layered architecture  

---

## 🏗️ Architecture

This project follows a layered architecture:

Controller → Service → Repository → Database

- **Controller Layer** → Handles HTTP requests  
- **Service Layer** → Contains business logic  
- **Repository Layer** → Database interactions  
- **Entity Layer** → Persistent data model  

---


---

## 🔗 REST API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | /api/employees | Create Employee |
| GET    | /api/employees | Get All Employees |
| GET    | /api/employees/{id} | Get Employee by ID |
| PUT    | /api/employees/{id} | Update Employee |
| DELETE | /api/employees/{id} | Delete Employee |

---
