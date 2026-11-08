# Student Management REST API

## 📌 Project Overview

The **Student Management REST API** is a backend application developed using Spring Boot that allows users to manage student records efficiently.

The application provides RESTful APIs to perform CRUD (Create, Read, Update, Delete) operations on student information. It uses Spring Data JPA for database operations and MySQL for storing student records.

## 🚀 Features

- Add new student records.
- Retrieve all student details.
- Retrieve a student by ID.
- Update existing student information.
- Delete student records.
- Perform database operations using Spring Data JPA.
- Test REST APIs using Postman.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Programming Language |
| Spring Boot | Backend Framework |
| Spring Data JPA | Database Operations |
| MySQL | Relational Database |
| Maven | Dependency Management |
| Postman | API Testing |
| Eclipse IDE | Development Environment |

## 🏗️ Project Architecture

The application follows a layered architecture:

1. **Controller Layer:** Handles incoming HTTP requests and returns responses.
2. **Service Layer:** Contains the business logic.
3. **Repository Layer:** Communicates with the database using Spring Data JPA.
4. **Entity Layer:** Represents student information as database entities.

## ⚙️ CRUD Operations

| Operation | Description |
|---|---|
| Create | Add a new student |
| Read | Retrieve student records |
| Update | Modify existing student details |
| Delete | Remove a student record |

## 🔗 API Endpoints

The following are example REST endpoint mappings. Adjust them if your controller uses different URLs.

| HTTP Method | Endpoint | Function |
|---|---|---|
| POST | `/students` | Add a student |
| GET | `/students` | Get all students |
| GET | `/students/{id}` | Get student by ID |
| PUT | `/students/{id}` | Update student |
| DELETE | `/students/{id}` | Delete student |

## 🗄️ Database

- Database: MySQL
- ORM: Hibernate (through Spring Data JPA)
- Stores student information in a relational database.

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/Nilavrodas31/Student-Management-RestApi.git
   ```

2. Open the project in Eclipse IDE.

3. Configure your MySQL database credentials in `application.properties`.

4. Make sure your MySQL server is running.

5. Update the database configuration according to your local setup.

6. Run the Spring Boot application.

7. Open Postman and test the REST API endpoints.

## 🎯 Learning Outcomes

- Understanding RESTful web services.
- Implementing CRUD operations using Spring Boot.
- Working with Spring Data JPA and MySQL.
- Understanding layered application architecture.
- Testing APIs using Postman.
- Connecting a Spring Boot application with a relational database.

## 👨‍💻 Author

**Nilavro Das**

GitHub: [Nilavrodas31](https://github.com/Nilavrodas31)

Project Repository: [Student-Management-RestApi](https://github.com/Nilavrodas31/Student-Management-RestApi)
