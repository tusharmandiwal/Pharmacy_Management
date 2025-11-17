# Pharmacy Management System

A full-stack Pharmacy Management System with a **React frontend** and **Spring Boot backend microservices**.

---

## Project Structure
pharmacy-management-system/
├── frontend/ # Vite + React frontend
└── pharmacy-backend/ # Backend microservices
├── inventory-service/
├── order-service/
├── payment-service/
└── user-service/


---

## Features

- User-friendly frontend with React + Vite
- Role-based access (Admin & User)
- Orders, Inventory, Cart, and Payment management
- Microservices architecture with JWT authentication
- Razorpay payment integration

---

## Technologies

- Frontend: React, Vite, JavaScript, HTML, CSS
- Backend: Java, Spring Boot, Spring Security, Spring Data JPA
- Database: MySQL or H2
- Payment: Razorpay
- Version Control: Git & GitHub

---

## Setup

### Frontend
```bash
cd frontend
npm install
npm run dev
Access at http://localhost:5173.
Backend
For each microservice:
cd pharmacy-backend/<service-name>
mvn clean install
mvn spring-boot:run


Author
Tushar Mandiwal
GitHub: https://github.com/tusharmandiwal

-

