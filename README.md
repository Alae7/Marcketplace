# 🌍 Universal Marketplace

**Universal Marketplace** is a full-stack web platform built with **Spring Boot** and **Angular** that connects buyers and sellers in a global online marketplace.  
It allows users to sell, buy, and manage products easily with a modern, secure, and responsive interface.

---

## 🚀 Key Features

### 🛒 Buyer Features
- Browse and search products by name, category, or price  
- View detailed product pages with descriptions and images  
- Add products to cart and proceed to checkout  
- Manage orders and view purchase history  

### 🏪 Seller Features
- Create and manage a seller profile  
- Add, edit, and delete product listings  
- Upload product images (via Cloudinary)  
- Track sales and manage inventory  

### ⚙️ Admin Features
- Manage users, sellers, and categories  
- Approve or disable seller accounts  
- Monitor transactions and platform activity  

---

## 🧱 Architecture Overview

The **Universal Marketplace** follows a **component-based microservice-inspired architecture** for scalability and maintainability.

### Backend – Spring Boot
- **Spring Boot 3+** – RESTful API backend  
- **Spring Data JPA & Hibernate** – ORM for database interaction  
- **Spring Security & JWT** – Authentication and authorization  
- **Spring Cloud Gateway** – API routing and service discovery (if microservices are used)  
- **MySQL** – Relational database  
- **Cloudinary** – Cloud image hosting  

### Frontend – Angular
- **Angular 17+** – Responsive web application  
- **Bootstrap / Tailwind CSS** – Modern UI styling  
- **Angular Router** – For navigation  
- **HTTPClient** – For API communication  

---

## 🔐 Security
- JSON Web Token (JWT)-based authentication  
- Role-based access control (Admin, Seller, Buyer)  
- Encrypted user passwords  
- Configured CORS policy for secure frontend-backend communication  

---

## 🧩 Prerequisites
- Java 17+  
- Maven 3+  
- Node.js (v18 or newer)  
- Angular CLI (`npm install -g @angular/cli`)  
- MySQL Database  
- Cloudinary account (for image uploads)

---

## 🧠 Technologies Used

| Layer | Technology |
|-------|-------------|
| Frontend | Angular, TypeScript, HTML5, CSS3, Bootstrap |
| Backend | Spring Boot, Spring Data JPA, Spring Security, JWT |
| Database | MySQL |
| Cloud | Cloudinary |
| Build Tools | Maven, Angular CLI |

---

## 💡 Future Enhancements
- Integration of a payment gateway (Stripe / PayPal)  
- AI-based product recommendations  
- Multi-language & multi-currency support  
- Mobile app (Angular + Ionic)                      

---

## 📄 License
This project is licensed under the **BSD 3-Clause License**.  

