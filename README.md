**note: we have stoped the backend deployment due to the cost so if you want to run our lms you can clone and run it 

## Learning Management System (LMS) – Project Overview

**Project Name**: Learning Management System (LMS)  
**Frontend**: React (Deployed on Netlify)  
**Backend**: Spring Boot (Temporarily stopped due to cost; previously deployed on Railway.app)  
**Database**: MySQL

### Project Description
This LMS project is designed to manage and streamline the educational experience for three key user roles: **Admin**, **Instructor**, and **Student**. The system supports course management, user authentication with OTP, and role-based dashboards.

---

### Roles & Functionalities

#### 1. **Admin**
- Login Credentials:  
  - **Email**: `admin@example.com`  
  - **Password**: `admin123`  
  - **Role**: `admin`
- Features:
  - Add and manage Students and Instructors
  - Create and manage Courses
  - Assign Courses to Students and Instructors

#### 2. **Instructor**
- Must be added by Admin
- Features:
  - View assigned courses
  - Add new courses
  - View course materials

#### 3. **Student**
- Must be added by Admin
- Features:
  - Access assigned courses
  - View course materials
  - Secure OTP-based login (6-digit code sent to registered email)

---

### Authentication Flow
- Students and Instructors receive a **6-digit OTP via email** upon login.
- Access to the dashboard is granted only after successful OTP verification.

---

### Development & Deployment
- **Frontend**: Built with React, deployed on **Netlify**
- **Backend**: Built with Spring Boot, connected to **MySQL** database (Currently offline)
- **Note**: To run the full system locally, clone the repository and run both frontend and backend services manually.

### Contribution
We welcome contributions! Feel free to fork the repository and suggest enhancements or new features.  
**Thank you for your support and interest in our LMS project!**
