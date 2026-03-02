# 🎓 Student Management System (Flask)

A web-based **Student Management System** built using **Flask (Python)** as the backend framework.  
This application allows administrators to manage student records efficiently with secure authentication.

---

## 📌 Project Overview

The Student Management System is designed to perform basic CRUD (Create, Read, Update, Delete) operations on student data. It also includes an authentication system to ensure secure access to the application.

This project demonstrates:
- Backend development using Flask
- Database integration
- Authentication implementation
- CRUD operations
- Frontend integration using HTML and CSS

---

## 🚀 Features

- ✅ User Authentication (Login & Logout)
- ➕ Add New Student
- 📄 View All Students
- ✏️ Edit Student Details
- ❌ Delete Student Record
- 🔐 Secure Access to Student Data

---

## 🛠️ Tech Stack

- **Backend:** Flask (Python)
- **Frontend:** HTML, CSS
- **Database:** SQLite
- **Authentication:** Flask Session / Flask-Login
- **Version Control:** Git & GitHub

---

## 📂 Project Structure

Student-Management-System/
│
├── static/             # CSS, JS, Images
├── templates/          # HTML Templates
├── app.py              # Main Flask Application
├── models.py           # Database Models (if separated)
├── requirements.txt    # Required Python Packages
└── README.md           # Project Documentation

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/student-management-system.git  
cd student-management-system

### 2️⃣ Create Virtual Environment

python -m venv venv

Activate virtual environment:

Windows:
venv\\Scripts\\activate

Mac/Linux:
source venv/bin/activate

### 3️⃣ Install Dependencies

pip install -r requirements.txt

### 4️⃣ Run the Application

python app.py

The application will run at:

http://127.0.0.1:5000/

---

## 🔐 Authentication

The system includes user authentication to:
- Prevent unauthorized access
- Protect student records
- Ensure secure login/logout functionality

Only authenticated users can:
- Add students
- Edit student details
- Delete student records

---

## 📊 Database

The database stores:
- Student ID
- Student Name
- Email
- Course
- Phone Number
- Other relevant details

You can modify the schema based on your requirements.

---

## 🎯 Learning Outcomes

Through this project, I learned:
- How to build routes in Flask
- How to implement CRUD operations
- How to connect Flask with a database
- How to implement authentication
- How to structure a full-stack web application

---

## 📌 Future Enhancements

- 🔎 Search and filter functionality
- 📥 Export student data (CSV/PDF)
- 📊 Dashboard with analytics
- 👥 Role-based authentication (Admin/User)
- 🌐 Cloud deployment

---

## 📜 License

This project is open-source and available under the MIT License.
"""
