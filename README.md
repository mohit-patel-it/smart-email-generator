# ✉️ Smart Email Generator

A **full-stack Smart Email Generator system** built using **Spring Boot (Backend)**,  
**React (Frontend)**, and a **Chrome Extension (Gmail Reply Generator)**.

This project demonstrates a **real-world, production-style architecture** where a **single backend** serves **multiple clients** — a web application and a browser extension — similar to modern SaaS products.

---

## 📌 Project Description

Smart Email Generator helps users:
- Generate professional email content via a web interface
- Generate smart replies directly inside Gmail using a Chrome extension

Both the **React web app** and the **Chrome Extension** use the **same Spring Boot backend APIs**, ensuring **code reuse, consistency, and scalability**.

---

## 🧩 System Architecture

Both the React web application and the Chrome Extension use the same
Spring Boot backend APIs, ensuring code reuse, consistency, and scalability.

```text
smart-email-generator/
│
├── backend-spring-boot/
│   ├── controllers/
│   ├── services/
│   ├── models/
│   └── REST APIs
│
├── frontend-react/
│   ├── components/
│   ├── pages/
│   └── UI for email generation
│
├── chrome-extension/
│   ├── content-script.js
│   ├── popup.html
│   └── Gmail reply integration
│
└── README.md
```

---

## ✨ Key Features

### 🌐 React Web Application
- Generate professional email content
- Select email tone (Formal / Professional / Casual)
- Clean and responsive UI
- Copy and reuse generated emails

### 🧩 Chrome Extension (Gmail Reply Generator)
- Works directly inside Gmail
- Generates smart replies for received emails
- Uses same backend APIs as web app
- Improves email productivity

### ⚙️ Spring Boot Backend
- RESTful API design
- Centralized email generation logic
- Shared services for web & extension
- Scalable and maintainable architecture

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5, CSS3
- Chrome Extension APIs

### Backend
- Java
- Spring Boot
- REST APIs
- Maven

### Tools & Platforms
- Git & GitHub
- Postman
- Chrome Developer Tools

---

## 🔗 API Reusability (Core Concept)

Both **React frontend** and **Chrome Extension** consume the **same backend APIs**.

✔ No duplicate business logic  
✔ Single source of truth  
✔ Easy maintenance  
✔ Industry-grade backend design  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/mohit-patel-it/smart-email-generator.git
