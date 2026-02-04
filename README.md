# 🔐 Spring Boot Login & Registration with JWT Authentication

This is a **Spring Boot backend project** that implements **User Login and Registration** using **Spring Security, JWT (JSON Web Token), and MySQL**.  
It is designed as a **resume-ready project** for Java / Spring Boot freshers.

---

## 🚀 Features

- User Registration (Sign Up)
- User Login (Authentication)
- JWT Token Generation
- Secure APIs using Spring Security
- Role-based access (USER / ADMIN)
- Password encryption using BCrypt
- RESTful APIs
- MySQL database integration

---

## 🛠️ Tech Stack

- Java 17+
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- Spring Data JPA (Hibernate)
- MySQL
- Maven
- IntelliJ IDEA

---

## 📂 Project Structure

src/main/java
└── com.codeWithRaman.implementation
├── config
├── controller
├── model
├── repository
├── service
└── RegisterAndLoginWithSecurityApplication.java


---

## 🔑 API Endpoints

### 🔸 Authentication APIs
| Method | Endpoint | Description |
|------|---------|------------|
| POST | `/auth/register` | Register a new user |
| POST | `/auth/login` | Login and get JWT token |

### 🔸 User APIs
| Method | Endpoint | Description |
|------|---------|------------|
| GET | `/user/profile` | Get user profile (JWT required) |

### 🔸 Admin APIs
| Method | Endpoint | Description |
|------|---------|------------|
| GET | `/admin/dashboard` | Admin access only |

---

## ⚙️ Configuration

### `application.properties`
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/jwt_db
spring.datasource.username=root
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

jwt.secret=your_secret_key
jwt.expiration=3600000
▶️ How to Run the Project
Clone the repository

git clone https://github.com/NandanR75/login-registration-jwt.git
Open in IntelliJ IDEA

Update MySQL credentials in application.properties

Run the application:

mvn spring-boot:run
Server will start at:

http://localhost:8080
🧪 Testing
You can test APIs using:

Postman

Swagger (if enabled)

Use JWT token in Authorization Header:

Authorization: Bearer <token>
📌 Resume Description (Use This)
Developed a Spring Boot application for secure user authentication using Spring Security and JWT. Implemented login, registration, role-based authorization, password encryption, and MySQL database integration.

👨‍💻 Author
Nandan R
