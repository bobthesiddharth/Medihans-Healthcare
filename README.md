Here is a **clean, professional, GitHub-ready README.md** you can directly paste into your repository:

---

# 🏥 Medihans HealthCare – Hospital Management System

**Live Demo:** [https://medihans.netlify.app/home](https://medihans.netlify.app/home)

A full-stack, production-ready **Hospital Management System** designed to digitize and automate hospital operations including patient management, appointments, billing, and analytics.

Built using **Angular, Spring Boot, MySQL, and AWS Cloud** with secure authentication and scalable architecture.

---

## 🚀 Overview

Medihans HealthCare is a centralized platform that replaces manual hospital workflows with an automated digital system.
It improves efficiency, security, and real-time collaboration among doctors, staff, and administrators.

---
<img width="1487" height="749" alt="Screenshot 2026-01-16 at 11 52 23 AM" src="https://github.com/user-attachments/assets/79b30e6f-3914-4196-a3d3-ee30057b4484" />


## 🧩 Problems Addressed

Many hospitals still rely on manual or semi-digital systems, leading to:

* ❌ Misplaced or inconsistent patient records
* ❌ Manual appointment conflicts
* ❌ Slow and error-prone billing
* ❌ Lack of centralized data access
* ❌ Poor security and scalability

### ✅ This Project Solves

* Centralized record management
* Real-time appointment scheduling
* Automated billing & invoices
* Secure role-based access
* Cloud-based scalable deployment
* Analytics for decision making

---

## 🛠 Tech Stack

### Frontend

* Angular 16
* TypeScript
* Bootstrap / Angular Material

### Backend

* Spring Boot
* Spring Security (JWT)
* Spring Data JPA
* Maven

### Database

* MySQL

### Cloud & DevOps

* AWS EC2
* AWS RDS
* CI/CD Pipelines
* Netlify (Frontend Hosting)

---<img width="1501" height="746" alt="Screenshot 2026-01-16 at 11 58 39 AM" src="https://github.com/user-attachments/assets/eeefd20a-cf54-4097-9ecf-ed469b7ab067" />
<img width="1497" height="724" alt="Screenshot 2026-01-16 at 11 58 59 AM" src="https://github.com/user-attachments/assets/646862f3-d8f5-46f7-8110-884c2f32cda1" />


## 💡 Key Functional Modules

### 1. Patient & Doctor Management

* Create, update, delete profiles
* Maintain medical history
* Prevent duplicate records
* Centralized database access

### 2. Appointment Scheduling

* Real-time booking
* Conflict detection
* Doctor availability logic
* Smooth scheduling workflow

### 3. Billing System

* Automated bill generation
* Service-based charge calculation
* Invoice download
* Payment history tracking

<img width="1497" height="742" alt="Screenshot 2026-01-16 at 11 54 53 AM" src="https://github.com/user-attachments/assets/eb314a65-1ac2-4538-bcf3-d648f4425bda" />

### 4. Security

* JWT Authentication
* Role-based access control
* Protected REST APIs
* Spring Security integration

### 5. Analytics Dashboard

* Patient trends
* Revenue reports
* Doctor workload statistics
* Exportable summaries

### 6. Cloud Deployment

* Backend deployed on AWS
* MySQL on AWS RDS
* Secure architecture
* CI/CD automated releases

---

## 📡 API Endpoints (Highlights)

* POST /auth/login – JWT Authentication
* POST /patients – Create patient
* GET /patients/{id} – Get patient details
* PUT /patients/{id} – Update patient
* DELETE /patients/{id} – Remove patient
* GET /doctors – View doctors
* POST /appointments – Schedule appointment
* GET /analytics/summary – Analytics data

---

## 📂 Project Structure

### Backend (Spring Boot)

```
/src
 ├── controller
 ├── service
 ├── repository
 ├── model
 └── security
```

### Frontend (Angular)

```
/src
 ├── app
 │   ├── components
 │   ├── services
 │   ├── guards
 │   └── models
 └── assets
```

---

## ▶️ Installation Guide

### 1. Clone Repository

```
git clone https://github.com/your-username/medihans-healthcare.git
```

---

### 2. Backend Setup

```
cd backend
mvn clean install
mvn spring-boot:run
```

---

### 3. Frontend Setup

```
cd frontend
npm install
ng serve -o
```

---

### 4. Database Configuration

* Create database: hospital_db
* Update credentials in application.properties

```
spring.datasource.url=jdbc:mysql://localhost:3306/hospital_db
spring.datasource.username=your_username
spring.datasource.password=your_password
```

---

## 📸Screenshots

 <img width="1487" height="751" alt="Screenshot 2026-01-16 at 11 52 39 AM" src="https://github.com/user-attachments/assets/67848873-58ee-41b4-ab88-18f6701261a2" />
---

## 🎯 Future Enhancements

* Email/SMS notifications
* Multi-hospital support
* Online payment integration
* AI-based appointment suggestions
* Mobile application

---

## 👤 Author

**Siddharth Nayak**
Full Stack Developer
Spring Boot | Angular | AWS | DevOps

---
