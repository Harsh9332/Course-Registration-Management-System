# 📚 Course Registration Management System

A full-stack web application designed to manage course registrations efficiently. This system allows users (students) to register for courses, view available courses, and manage their enrollment details. Admins can manage the course list, student records, and overall course registrations.

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap  
- **Backend**: PHP  
- **Database**: MySQL  
- **Server**: XAMPP / Apache

## 🚀 Features

### 👨‍🎓 Student Panel:
- User registration and login
- Browse available courses
- Register for courses
- View enrolled courses
- Profile management

### 👨‍💼 Admin Panel:
- Secure admin login
- Add/update/delete courses
- Manage student data
- View and manage all registrations
- Dashboard with key statistics

## Move the project to your XAMPP htdocs folder
- xampp/htdocs/Course-Registration-Management-System 

## Start Apache and MySQL using XAMPP Control Panel

##Import the database
- Open phpMyAdmin (http://localhost/phpmyadmin)

- Create a new database (e.g., course_registration)

- Import the provided SQL file located in the project folder (course_registration.sql if available)

## Edit DB credentials if needed
- Open dbconn.php and update:
  $host = "localhost";
  $username = "root";
  $password = "";
  $dbname = "course_registration";

## 🔐 Login Credentials (Default)
Admin
- Username: admin

- Password: admin123
