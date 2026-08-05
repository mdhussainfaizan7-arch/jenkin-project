# 🚀 AWS Three-Tier Employee Registration Application
CI/CD: Jenkins Pipeline for automated build and deployment

A modern Three-Tier Web Application built using **HTML, CSS, JavaScript, Spring Boot, MySQL, and AWS EC2**. This project demonstrates the deployment of a complete web application following a three-tier architecture.

---

## 📌 Project Overview

This project is designed to demonstrate how a three-tier architecture works in a real-world environment.

The application allows users to register employee details through a web interface. The data is processed by a Spring Boot REST API and stored in a MySQL database.

---

## 🏗️ Three-Tier Architecture

```
                +----------------------+
                |      Web Browser     |
                +----------+-----------+
                           |
                           |
                           ▼
            +----------------------------+
            |        Presentation Tier   |
            | HTML • CSS • JavaScript    |
            +-------------+--------------+
                          |
                          |
                          ▼
            +----------------------------+
            |      Application Tier      |
            |     Spring Boot REST API   |
            +-------------+--------------+
                          |
                          |
                          ▼
            +----------------------------+
            |        Database Tier       |
            |           MySQL            |
            +----------------------------+
```

---

## ✨ Features

- Employee Registration Form
- Responsive User Interface
- REST API Integration
- Spring Boot Backend
- MySQL Database Connectivity
- AWS EC2 Deployment
- Clean Three-Tier Architecture

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- Spring Boot
- Maven

### Database
- MySQL

### Cloud & DevOps
- AWS EC2
- Ubuntu Linux
- Git
- GitHub
- SSH

---

## 📁 Project Structure

```
Jenkins-project/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   ├── resources/
│   │   └── static/
│   │
│   └── test/
│
├── pom.xml
├── README.md
└── target/
```

---

## ⚙️ Prerequisites

- Java 17+
- Maven
- MySQL
- Git
- AWS EC2 (Ubuntu)

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/mdhussainfaizan7-arch/Jenkins-project.git
```

---

### 2. Navigate to the Project

```bash
cd Jenkins-project
```

---

### 3. Configure MySQL

Create a database.

```sql
CREATE DATABASE mydb;
```

Update your database credentials in:

```
src/main/resources/application.properties
```

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/mydb
spring.datasource.username=root
spring.datasource.password=your_password
```

---

### 4. Build the Project

```bash
mvn clean package
```

---

### 5. Run the Application

```bash
java -jar target/*.jar
```

or

```bash
mvn spring-boot:run
```

---

### 6. Open in Browser

```
http://localhost:8080
```

---

## 📷 Screenshots

### 🖥️ Application UI

(Add your UI screenshot here)

---

### ☁️ AWS EC2 Instance

(Add EC2 screenshot here)

---

### 🗄️ MySQL Database

(Add MySQL screenshot here)

---

### 💻 Spring Boot Running

(Add terminal screenshot here)

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Three-Tier Architecture
- REST API Development
- Spring Boot Fundamentals
- MySQL Integration
- AWS EC2 Deployment
- Linux Server Administration
- Git & GitHub Workflow
- End-to-End Application Deployment

---

## 👨‍💻 Author

Mohammed Hussain 

📧 Email: mdhussainfaizan7@gmail.com

💼 LinkedIn:
https://www.linkedin.com/in/mohammed-hussain-62a14b418

🐙 GitHub:
https://github.com/mdhussainfaizan7-arch

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

Feedback and suggestions are always welcome!
