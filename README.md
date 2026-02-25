# Ecommerce-Microservices-System

## 📌 Overview
This project is a microservices-based backend system built using Spring Boot. It demonstrates service-to-service communication, service discovery, and secure API interactions.

---

## 🧱 Architecture

- Eureka Server (Service Registry)
- User Service (JWT Authentication)
- Order Service (Business Logic + Feign Client)
- API Gateway (In Progress)

---

## ⚙️ Technologies Used

- Java 17
- Spring Boot
- Spring Cloud (Eureka, OpenFeign)
- Spring Security (JWT)
- MySQL
- Maven

---

## 🔗 Microservices Communication

- Order Service communicates with User Service using OpenFeign
- JWT token is propagated between services

---

## 🔐 Security

- JWT-based authentication implemented in User Service
- Token propagation using Feign Interceptor

---

## 📦 APIs

### User Service
- Register User
- Get User by ID
- Get All Users

### Order Service
- Create Order
- Get Order by ID
- Get Orders by User

---

## 🚀 How to Run

1. Start Eureka Server
2. Start User Service
3. Start Order Service
4. Test APIs using Postman

---

## 📌 Future Enhancements

- API Gateway
- Centralized Security
- Circuit Breaker (Resilience4j)
- Kafka Integration

---

## 👨‍💻 Author

Mohd Fahad Ansari
