# Hospital Management System

A full-stack Hospital Management System developed using Spring Boot, MySQL, and Eclipse IDE.  
This project helps manage hospital operations such as patient records, doctor details, appointments, billing, and administration efficiently.

---

## 📌 Project Overview

The Hospital Management System is designed to simplify hospital workflows and improve data management.  
It provides a centralized platform for handling patient information, doctor schedules, appointments, and medical records.

---

## 🚀 Features

- Patient Registration and Management
- Doctor Management
- Appointment Booking System
- Admin Dashboard
- Billing and Payment Management
- Medical Record Storage
- Search and Update Patient Details
- Secure Database Connectivity
- User-Friendly Interface

---

## 🛠️ Technologies Used

| Technology | Description |
|------------|-------------|
| Java | Programming Language |
| Spring Boot | Backend Framework |
| MySQL | Database Management |
| HTML/CSS | Frontend Design |
| Bootstrap | Responsive UI |
| Eclipse IDE | Development Environment |
| JDBC / JPA | Database Connectivity |

---

## 🏗️ System Modules

### 1. Admin Module
- Manage doctors and patients
- View appointments
- Monitor hospital records

### 2. Doctor Module
- View patient details
- Update treatment information
- Manage appointments

### 3. Patient Module
- Register/Login
- Book appointments
- View medical records

### 4. Billing Module
- Generate bills
- Manage payment records

---

## ⚙️ Installation Steps

### Prerequisites
- Java JDK 8 or above
- MySQL Server
- Eclipse IDE
- Maven

### Steps to Run the Project

1. Clone the repository

```bash
git clone <repository-link>
```

2. Open the project in Eclipse IDE

3. Configure MySQL Database

Create a database named:

```sql
hospital_management
```

4. Update database credentials in `application.properties`

Example:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/hospital_management
spring.datasource.username=root
spring.datasource.password=yourpassword
```

5. Run the Spring Boot application

6. Open browser and visit:

```bash
http://localhost:8080
```

---

## 📂 Project Structure

```plaintext
HospitalManagementSystem/
│
├── src/main/java
├── src/main/resources
├── templates
├── static
├── pom.xml
└── application.properties
```

---

## 🗄️ Database

Database used: MySQL

Main Tables:
- Patients
- Doctors
- Appointments
- Billing
- Admin

---

## 🎯 Objectives

- Reduce manual hospital management work
- Improve data accuracy
- Provide secure and centralized record management
- Enhance appointment scheduling efficiency

---

## 📸 Future Enhancements

- Online Payment Integration
- Email/SMS Notifications
- AI-based Appointment Suggestions
- Cloud Deployment
- Role-Based Authentication



## 📜 License

This project is developed for educational and learning purposes.
