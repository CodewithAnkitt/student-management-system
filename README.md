# Student Management System

A web-based Student Management System built with Django. This application allows administrators, staff, and students to manage academic activities, attendance, notifications, and more.

## Features

- **User Roles:**
  - Admin (HOD)
  - Staff
  - Student
- **Authentication:** Email-based login system with custom user model
- **Attendance Management:** Track and manage student attendance
- **Session Management:** Academic session creation and management
- **Notifications:** Send notifications to students and staff
- **Profile Management:** Edit and view user profiles
- **Feedback System:** Students and staff can submit feedback
- **Leave Management:** Students and staff can apply for leave
- **Course & Subject Management:** Add, edit, and delete courses and subjects
- **Firebase Integration:** For push notifications (FCM token support)

## Tech Stack
- Python 3
- Django 4.2
- SQLite (default, can be switched to PostgreSQL/MySQL)
- Bootstrap (for UI)
- JavaScript, jQuery

## Setup Instructions

1. **Clone the repository**
   ```sh
   git clone <repo-url>
   cd Student-Management-system
   ```
2. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
3. **Apply migrations**
   ```sh
   python manage.py migrate
   ```
4. **Create a superuser**
   ```sh
   python manage.py createsuperuser
   ```
5. **Run the development server**
   ```sh
   python manage.py runserver
   ```
6. **Access the app**
   - Open your browser and go to `http://127.0.0.1:8000/`

## Directory Structure
- `main_app/` - Main Django app with models, views, templates, and static files
- `student_management_system/` - Project settings and configuration
- `media/` - Uploaded media files (profile pictures, etc.)
- `static/` - Static files (CSS, JS, images)

## Requirements
See `requirements.txt` for all dependencies.

## License
This project is for educational purposes.
