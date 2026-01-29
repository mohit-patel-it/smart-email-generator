# ✉️ Smart Email Generator & Gmail AI Reply Extension

A **full-stack, production-style Smart Email Generator system** built using  
**Spring Boot (Backend)**, **React (Frontend)**, and a **Chrome Extension** that injects an **AI Reply button directly into Gmail**.

The project demonstrates a **real-world SaaS-style architecture** where a **single backend** serves **multiple clients**:
- A React web application for email generation
- A Chrome Extension for smart Gmail replies

---

## 📌 Project Overview

Smart Email Generator helps users:
- Generate professional emails using a React web application
- Generate AI-powered replies directly inside Gmail using a Chrome Extension

Both the **React app** and the **Chrome Extension** communicate with the **same Spring Boot backend APIs**, ensuring **code reuse, consistency, and scalability**.

---

## 🧩 System Architecture

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
│   └── Email Generator UI
│
├── chrome-extension/
│   ├── content-script.js
│   ├── popup.html
│   └── Gmail AI Reply Button
│
├── screenshots/
│   ├── web-before.png
│   ├── web-after.png
│   ├── gmail-before.png
│   └── gmail-after.png
│
└── README.md
```
✨ Key Features
🌐 React Web Application
Generate professional email content

Select tone (Formal / Professional / Casual)

Clean and responsive UI

Copy generated email content

🧩 Chrome Extension – Gmail AI Reply Generator
Injects an AI Reply button directly into Gmail

Extracts email content from Gmail

Sends content to Spring Boot backend

Inserts AI-generated reply into Gmail compose box

⚙️ Spring Boot Backend
RESTful API design

Centralized email generation logic

Shared backend for web app & extension

Scalable and maintainable architecture

📸 Application Screenshots
🌐 Email Generator – React Web App
🔹 Before (Empty / Manual Email Writing)

🔹 After (AI Generated Email)

🧩 Gmail Chrome Extension – AI Reply Button
🔹 Before (Normal Gmail Interface)

🔹 After (AI Reply Button & Generated Reply)

🔗 Shared Backend Design (Important Highlight)
Both the React web application and the Gmail Chrome Extension use the same Spring Boot backend APIs.

React Web App ─────▶ Spring Boot REST API ─────▶ Email Generator Logic
Gmail Extension ───▶ Spring Boot REST API ─────▶ Same Logic
✔ No duplicate business logic
✔ Single source of truth
✔ Easy maintenance and scalability

⚙️ Installation & Setup Guide
1️⃣ Clone Repository
git clone https://github.com/USERNAME/smart-email-generator.git
2️⃣ Backend Setup (Spring Boot)
cd backend-spring-boot
mvn clean install
mvn spring-boot:run
Backend runs on:

http://localhost:8080
3️⃣ Frontend Setup (React)
cd frontend-react
npm install
npm start
Frontend runs on:

http://localhost:3000
4️⃣ Chrome Extension Setup
Open Chrome → chrome://extensions

Enable Developer Mode

Click Load Unpacked

Select chrome-extension/ folder

Open Gmail and use the AI Reply button

🧠 Technical Flow (Interview Ready)
User opens Gmail and clicks the AI Reply button

Chrome Extension extracts email content from Gmail DOM

Sends content to Spring Boot REST API

Backend generates reply

Extension inserts reply into Gmail compose box

## 📸 Application Screenshots

### 🌐 Email Generator – React Web Application

#### 🔹 Before (Manual Email Writing)
![Before Email Generation](photos/before-generate.png)

#### 🔹 After (AI Generated Email)
![After Email Generation](photos/after-generate.png)

---

### 🧩 Gmail Chrome Extension – AI Reply Generator

#### 🔹 Before (Default Gmail Interface)
![Before Gmail Extension](photos/before-extension.png)

#### 🔹 After (AI Reply Button & Generated Reply)
![After Gmail Extension](photos/after-extension.png)


🛠️ Tech Stack
Frontend
React.js

JavaScript (ES6+)

HTML5, CSS3

Chrome Extension
JavaScript

Chrome Extension APIs

Content Scripts

DOM Manipulation

Backend
Java

Spring Boot

REST APIs

Maven

🔮 Future Enhancements
AI model integration (OpenAI / LLMs)

User authentication & email history

Tone & language selection

OAuth integration with Gmail

Cloud deployment (AWS / Render)

👨‍💻 Author
Mohit Patel
Java Full Stack Developer
🔗 LinkedIn: https://www.linkedin.com/in/mohit-patel-5b10532b3
