# 🧠 E-Commerce REST API System

🔗 API Documentation: https://documenter.getpostman.com/view/32857096/2sA3kPo4Fh

---

## 📌 Overview

This project is a **scalable RESTful API system** for an e-commerce platform.

It provides secure and structured endpoints for managing:

- Users authentication
- Products
- Orders
- Data relationships between collections

The system is built following **backend best practices**, focusing on security, validation, and maintainability.

---

## ⚙️ Tech Stack

- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- JOI Validation
- dotenv

---

## ✨ Core Features

- 🔐 Authentication & Authorization middleware (JWT-based)
- 🧾 Input validation using JOI for all requests
- 🧠 Centralized error handling system
- 🗂️ Relational data handling between collections
- 🧹 Automatic cleanup of related documents on deletion
- 🔒 Environment variables for secure configuration
- 🧾 API documentation using Postman

---

## 🧠 Architecture Highlights

The system is designed with backend scalability in mind:

- **MVC-like structure (Models / Controllers / Routes)**
- **Middleware-driven request pipeline**
- **Reusable validation layer**
- **Separation of business logic from routes**
- **Central error handling strategy**

This ensures the API can be easily extended and maintained in real-world applications.

---

## 🔐 Security Layer

- Protected routes using JWT authentication
- Authorization middleware for role-based access control
- Input sanitization and validation via JOI
- Sensitive data stored using environment variables (.env)

---

## 📦 Data Handling

- Mongoose schemas for structured data modeling
- Cascading deletion logic for related documents
- Consistent API responses across endpoints

---

## 📖 API Documentation

Full API documentation is available via Postman:

👉 https://documenter.getpostman.com/view/32857096/2sA3kPo4Fh

---

## 🚀 Getting Started

### Prerequisites

- Node.js >= 14
- MongoDB instance
- npm or yarn

---

### Installation

```bash
git clone https://github.com/yourusername/ecommerce-app.git
cd ecommerce-app
npm install
