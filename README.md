# E-Commerce Full Stack Application

## 📌 Overview
This project is a full stack web application built using:
- Frontend: React
- Backend: Spring Boot
- Database: H2 / MySQL

The application allows users to:
- Register and login
- View products
- Manage products (Admin only)
- Role-based access control (Admin/User)

---

## 🔐 Features

- JWT Authentication
- Role-Based Access Control (RBAC)
- Admin & User roles
- Product CRUD operations
- User profile management
- Google SSO (OAuth2) support

---

## 🛠️ Tech Stack

### Frontend
- React JS
- Axios
- React Router

### Backend
- Spring Boot
- Spring Security
- Spring Data JPA

### Database
- H2 / MySQL

---

## ▶️ How to Run

### Backend
cd backend
mvn spring-boot:run

Runs on:
http://localhost:8080

---

### Frontend
cd frontend
npm install
npm start

Runs on:
http://localhost:3000

---

## 👤 Users

Admin:
username: admin
password: admin

User:
username: user
password: user

---

## 📌 Notes
- Admin can add, update, delete products
- User can only view products
