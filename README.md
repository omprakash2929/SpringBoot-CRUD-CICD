# 🚀 CI/CD Pipeline for Spring Boot CRUD App on AWS ECS (GitLab)

This project demonstrates how to **automate the deployment of a Java Spring Boot CRUD application** using a **GitLab CI/CD pipeline** with **AWS ECS, ECR, and RDS MySQL**.  
It showcases containerization with Docker, infrastructure automation, and continuous delivery best practices.

---

## 📌 Key Highlights

- ✅ Spring Boot CRUD web application with MySQL database  
- ✅ Containerized using Docker & deployed on **AWS ECS (Fargate)**  
- ✅ **GitLab CI/CD pipeline** for automated build, test & deploy  
- ✅ AWS RDS MySQL integration for persistence  
- ✅ Zero-downtime deployment approach  
- ✅ Secure, scalable & production-ready workflow  

---

## 🛠️ Tech Stack

- **Backend**: Java, Spring Boot, Spring Data JPA, Spring MVC, Thymeleaf  
- **Database**: MySQL (AWS RDS)  
- **DevOps Tools**: GitLab CI/CD, Docker, AWS ECS, ECR, RDS, EFS  
- **IDE**: Spring Tool Suite (STS)  
- **Version Control**: Git/GitLab  

---

## 📊 Architecture Diagram

![CI/CD Pipeline Architecture](/src/main/resources/static/images/Implement%20GitLab%20CICD%20Pipeline%20on%20AWS%20ECS%20with%20RDS%20MySQL%20for%20Java%20Spring%20Boot%20Application.webp)

---

## 🎥 Demo

![Pipeline Demo](/src/main/resources/static/images/Implement%20GitLab%20CICD%20Pipeline%20on%20AWS%20ECS%20with%20RDS%20MySQL%20for%20Java%20Spring%20Boot%20Application.gif)

---

## 📝 Features of the CRUD Application

- 🔹 User registration with password encryption  
- 🔹 Image upload support  
- 🔹 Pagination & flash messages  
- 🔹 Custom error handling (404, 500, etc.)  
- 🔹 Secure and optimized database design  

---

## ⚡ Setup & Usage

### 1️⃣ Database Setup
```sql
CREATE DATABASE boot_crud_db;
USE boot_crud_db;

CREATE TABLE users (
  id BIGINT(20) NOT NULL AUTO_INCREMENT,
  dob DATE DEFAULT NULL,
  email VARCHAR(255) UNIQUE,
  name VARCHAR(255),
  password VARCHAR(255),
  image VARCHAR(255),
  PRIMARY KEY (id)
);
```
### 📥 Insert Sample Data

```sql
INSERT INTO users (dob, email, name, password, image) VALUES
('2025-07-26', 'omprakash@gmail.com', 'omprakash', 'hashed_password', 'sample.jpg');
```

### 🚀 Run the Application
  - Import project into Spring Tool Suite (STS) as a Maven project
  - Build & update Maven dependencies
  - Run the main class:
  ```
  src/main/java/com/crudapp/SpringBootCrudApplication.java
```
- Open http://localhost:8080 in your browser
---
### 🙏 Acknowledgements
##### Special thanks to @ProjectsAndPrograms for the base crud-spring-boot-thymeleaf project.

## 🤝 Contributing
#### Contributions are welcome!
- Fork the repo
- Create a new branch (feature/your-feature)
- Submit a pull request 🚀

# 💡 Why this Project Matters?
#### This project is a real-world DevOps use case combining:
- Software Engineering (Spring Boot)
- DevOps (CI/CD, AWS, Docker, GitLab)

#### It demonstrates my ability to design, build, and deploy end-to-end applications with automation and cloud scalability.
