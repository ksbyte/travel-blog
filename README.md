# Travel Blog Application (Spring Boot)

## Project Overview

The Travel Blog Application is a simple web-based blogging platform developed using **Spring Boot**. It allows users to create, manage, and display travel blog posts through a structured backend using the MVC architecture.

The project demonstrates the implementation of **REST APIs, service layer architecture, and repository-based database interactions**.

---

## Tech Stack

Backend

* Java
* Spring Boot
* Spring Data JPA
* Maven

Frontend

* HTML
* JavaScript

---

## Project Structure

src/main/java/com/travelblog

### Controller Layer

**BlogPostController.java**

Handles HTTP requests and exposes REST endpoints for blog operations such as creating and retrieving blog posts.

---

### Model Layer

**BlogPost.java**

Represents the blog post entity. It defines the data structure for storing blog post information.

Example fields:

* id
* title
* content
* author
* createdDate

---

### Repository Layer

**BlogPostRepository.java**

Handles database operations using Spring Data JPA. It provides methods for saving, retrieving, and managing blog posts.

---

### Service Layer

**BlogPostService.java**

Contains business logic for blog post operations and interacts with the repository layer.

---

### Application Entry Point

**TravelblogApplication.java**

Main class responsible for starting the Spring Boot application.

---

## Frontend

src/main/resources/static

### index.html

Main web page used to display or interact with blog posts.

### script.js

Handles client-side logic and communicates with backend APIs.

---

## How to Run the Project

### 1 Clone the repository

git clone https://github.com/your-username/travel-blog.git

---

### 2 Navigate to the project directory

cd travel-blog

---

### 3 Run the Spring Boot application

Using Maven

./mvnw spring-boot:run

or

mvn spring-boot:run

---

### 4 Open in browser

http://localhost:8080

---

## Features

* Create travel blog posts
* View blog posts
* MVC architecture implementation
* REST API based backend
* Simple frontend integration

---

## Future Improvements

* Add database integration (MySQL / PostgreSQL)
* Implement authentication and authorization
* Add comment system
* Add image upload functionality
* Improve UI design

---

## Author

Karan Sharma
Software Test Engineer | Java | Selenium | Manual Testing | Performance Testing
