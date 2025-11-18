# 🎓 Student Management System 🏫  
### _A Complete Django-Based Platform for Managing Students, Staff, Courses & Academic Workflows ✨_

---

<p align="center">
  <img src="https://img.shields.io/badge/Built%20with-Django-0C4B33?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Backend-Python%203.8+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Frontend-HTML%2C%20CSS%2C%20JS-1572B6?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/Authentication-Custom%20Email%20Login-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge"/>
</p>

---

## 🧠 Project Overview

The **Student Management System** is a comprehensive, web-based platform built with **Django** to help educational institutions manage all academic workflows — including students, staff, attendance, results, notifications, and more.  
It provides **role-based dashboards** for **Admin (HOD)**, **Staff**, and **Students**, ensuring everyone gets the right tools with the right access.

---

## 🌟 Key Technical Highlights

| Feature Area | Description |
|--------------|-------------|
| **Framework** | Django 4.2.24 (Python-based MVT architecture) |
| **Frontend** | HTML, CSS, JavaScript templates |
| **Database** | SQLite (default) with support for PostgreSQL/MySQL |
| **Authentication** | Custom Email-Based Login System |
| **Notifications** | SMTP-based Email Alerts |
| **Static Files** | WhiteNoise for production-ready serving |
| **Deployment-Ready** | Gunicorn + Nginx supported |

---

## ⚙️ Core Features

### 🏛️ Admin (HOD) Features
- Manage **Staff** (add, edit, delete)  
- Manage **Students** (CRUD operations)  
- Manage **Courses** & **Subjects**  
- Manage **Session Years**  
- View & control **Attendance**   
- Send notifications to Students & Staff  
- Review & reply to feedback  
- Approve/Reject **Leave Applications**  
- Dashboard with useful statistics  

---

### 👨‍🏫 Staff Features
- Take & update student **attendance**  
- Add/edit **student results**  
- Submit **leave applications**  
- Give **feedback to admin**  
- View assigned subjects/students  
- Receive notifications  
- View & update profile  

---

### 🎓 Student Features
- View **attendance report**  
- View **exam results**  
- Apply for **leave**  
- Submit feedback  
- Receive admin notifications  
- View personal profile & course details  

---

## 💻 Technology Stack

- **Backend:** Django 4.2.24  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** SQLite / PostgreSQL / MySQL  
- **Authentication:** Email-based login  
- **Static Files:** WhiteNoise  
- **Email Service:** SMTP backend (Gmail supported)  
- **Deployment:** Gunicorn-ready  

---

## 🚀 Quick Start — Installation

### 1️⃣ Prerequisites
- Python 3.8+
- pip
- Virtual environment (recommended)

---

### 2️⃣ Clone the Repository

```bash
git clone <repository-url>
cd student_management_system
```

### 3️⃣ Create & Activate Virtual Environment
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux / Mac
python3 -m venv venv
source venv/bin/activate
```

### 4️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 5️⃣ Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
### 6️⃣ Create Superuser (Admin)
```bash
python manage.py createsuperuser
```
### 7️⃣ Start Development Server
```bash
python manage.py runserver
Visit 👉 http://127.0.0.1:8000/
```

## 📁 Project Structure
```cpp
student_management_system/
├── main_app/
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   ├── hod_views.py
│   ├── staff_views.py
│   ├── student_views.py
│   ├── forms.py
│   ├── urls.py
│   ├── middleware.py
│   ├── EmailBackend.py
│   └── EditResultView.py
├── student_management_system/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── media/
├── static/
├── db.sqlite3
├── manage.py
└── requirements.txt
```
### 🗂️ Database Models
**Includes:**
 - CustomUser (Email login)
 - Admin
 - Staff
 - Student
 - Course
 - Subject
 - SessionYear
 - Attendance
 - AttendanceReport
 - LeaveReportStudent / LeaveReportStaff
 - Feedback Models
 - Notification Models
 - StudentResult

