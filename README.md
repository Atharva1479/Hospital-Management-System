# Hospital-Management-System

## 📌 Project Overview
The **Hospital Management System (HMS)** is a full-stack web application designed to streamline hospital operations. It enables **patients, doctors, and administrators** to manage appointments, medical records, and user information efficiently. The system ensures secure authentication and role-based access control.

## 🛠 Tech Stack
- **Frontend:** React, React Router, MDB React UI, FontAwesome
- **Backend:** Spring Boot, Spring Security, JWT Authentication
- **Database:** MySQL
- **Version Control:** Git & GitHub

## 🎯 Features
### **🔹 Patients**
- Sign up, log in, and manage profile
- Book and view doctor appointments
- Search for doctors by specialization & city
- Access blood donor information

### **🔹 Doctors**
- Register and update profile
- Manage patient details
- View and update appointment slots

### **🔹 Admin**
- Manage doctors and patients
- Monitor appointments and system usage

### **🔹 Other Features**
- Secure JWT-based authentication
- Password reset system
- Role-based access control (Admin, Doctor, Patient)
- Blood donor management

## 🏗 Project Setup
### **1️⃣ Clone the Repository**
```sh
 git clone <repository-url>
 cd hospital-management-system
```

### **2️⃣ Frontend Setup (React)**
```sh
 cd frontend
 npm install
 npm start
```

### **3️⃣ Backend Setup (Spring Boot)**
```sh
 cd backend
 mvn clean install
 mvn spring-boot:run
```

### **4️⃣ Database Setup (MySQL)**
- Create a database named `hospital_db`
- Update `application.properties` with MySQL credentials

## 🚀 Deployment
- Frontend: **Vercel / Netlify** (Recommended)
- Backend: **Heroku / AWS / Render** (Recommended)
- Database: **Cloud MySQL (AWS RDS / Firebase / Supabase)**

## 📝 Git Workflow
1. **Create a new branch for features:**
   ```sh
   git checkout -b feature-name
   ```
2. **Commit changes after each feature:**
   ```sh
   git add .
   git commit -m "Added feature-name"
   ```
3. **Push to GitHub:**
   ```sh
   git push origin feature-name
   ```
4. **Create a Pull Request (PR) and merge into `main`**

## 📄 License
This project is for educational purposes only.

## 🙌 Contributors
- **Your Name** - Full Stack Developer
- **[Add team members if any]**

## 📧 Contact
For any inquiries, reach out at: **your-email@example.com**
