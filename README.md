<h1 align="center">📇 Smart Contact Manager</h1>

<p align="center">
A full-stack secure contact management application with authentication, dashboard, and advanced contact features
</p>

<p align="center">

<img src="https://img.shields.io/badge/BACKEND-Spring%20Boot-6c757d?style=for-the-badge&labelColor=555&color=8ac926"/>
<img src="https://img.shields.io/badge/FRONTEND-Thymeleaf%20%7C%20Tailwind-6c757d?style=for-the-badge&labelColor=555&color=1982c4"/>
<img src="https://img.shields.io/badge/DATABASE-MySQL-6c757d?style=for-the-badge&labelColor=555&color=f9844a"/>

<br/>

<img src="https://img.shields.io/badge/SECURITY-Spring%20Security-6c757d?style=for-the-badge&labelColor=555&color=ef476f"/>
<img src="https://img.shields.io/badge/STATUS-Completed-6c757d?style=for-the-badge&labelColor=555&color=06d6a0"/>

</p>

---

## 📌 Overview
Smart Contact Management System is a full-stack web application that allows users to securely manage their contacts. It includes authentication, role-based access, contact CRUD operations, image uploads, and advanced features like search, pagination, and social login.

The application is built using **Spring Boot** for backend and **Thymeleaf + Tailwind CSS** for frontend, ensuring a responsive and user-friendly experience.

---

## 🚀 Features

### 🔐 Authentication & Security
- User signup & login system
- Spring Security integration
- Role-based authorization
- OAuth login (Google & GitHub)

### 📊 Dashboard
- User dashboard after login
- Contact overview and management panel

### 📇 Contact Management
- Add, update, delete contacts
- Upload contact images (cloud integration)
- View detailed contact information (AJAX-based)

### 🔍 Advanced Functionalities
- Search contacts by multiple fields
- Pagination for large datasets
- Form validation (custom + backend validation)
- Error handling and alert messages

### 🎨 UI/UX
- Fully responsive design
- Dark mode support 🌙
- Dynamic navbar and layouts using Thymeleaf fragments

---

## ⚙️ Tech Stack

### 🖥️ Backend
- Spring Boot
- Spring Security
- Hibernate / JPA
- REST APIs

### 🎨 Frontend
- Thymeleaf
- HTML5, CSS3
- Tailwind CSS

### 🗄️ Database
- MySQL

### 🔧 Tools
- Git & GitHub
- Postman
- VS Code / IntelliJ

---

## 📂 Project Structure
src/
├── controller/
├── service/
├── repository/
├── entity/
├── config/
└── templates/

---

## 🧠 Key Implementations
- Secure authentication with **Spring Security**
- OAuth integration for **Google & GitHub login**
- Efficient data handling using **Hibernate & JPA**
- Image upload and storage integration
- AJAX-based dynamic content loading
- Pagination & search optimization

---

## 📸 Screenshots (Add your own)
- Login Page  
- Dashboard  
- Contact List  
- Add Contact Form  

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smart-contact-manager.git
2. Navigate to project:
cd smart-contact-manager
3. Configure database in application.properties
4. Run the application:
   mvn spring-boot:run
5. Open in browser
