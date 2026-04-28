# 🔐 JWT Authentication & E-Commerce Backend System

## 📌 Project Description

This is a Spring Boot based backend application that implements JWT (JSON Web Token) authentication with role-based authorization. It supports Admin and User roles, product management, cart system, and payment integration. The application runs on localhost and APIs can be tested via browser or API tools.

---

## 🚀 Features

* User Registration & Login
* JWT Authentication & Authorization
* Role-Based Access Control (Admin/User)
* Predefined Admin Account
* Product Management (CRUD)
* Shopping Cart Functionality
* Secure Payment Integration
* Runs on Localhost (Browser Supported)

---

## 🌐 Application Access

* Runs on: `http://localhost:8081`
* APIs can be accessed via:

  * Browser (for GET APIs)
  * Postman (for all APIs)

---

## 🔐 Role-Based Access

### 👑 Admin

* Add / Update / Delete products
* Full access to product APIs

### 👤 User

* View products
* Add/remove items in cart
* Perform payment

---

## 🛡️ Security

* JWT token-based authentication
* Spring Security configuration
* Role-based authorization (`ROLE_ADMIN`, `ROLE_USER`)

---

## 🛠️ Tech Stack

* Java
* Spring Boot
* Spring Security
* JWT
* Hibernate / JPA
* MySQL
* Maven

---

## 🔑 API Endpoints

### 🔹 Auth APIs

* POST `/api/auth/register`
* POST `/api/auth/login`

### 🔹 Admin APIs

* POST `/api/products`
* PUT `/api/products/{id}`
* DELETE `/api/products/{id}`

### 🔹 User APIs

* GET `/api/products`
* POST `/api/cart/add/{productId}`
* GET `/api/cart`

---

## 💳 Payment

* Order creation
* Payment verification
* Secure transaction flow

---

## ▶️ How to Run

1. Clone repository
2. Open in Eclipse / STS
3. Configure MySQL
4. Add payment keys
5. Run application
6. Open browser: `http://localhost:8081`

---

## 📷 Screenshots

AdminHome.png,AdminLogin.png,CustomerHome.png,CustomerLogin.png,CustomerSignUp.png,ProductCrud.png,ViewCart.png,WelcomePage.png

---

## 📌 Default Admin Credentials

Email: admin
Password: admin123

---

## 👩‍💻 Author

Monija
