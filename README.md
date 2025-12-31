# Secure Web Application (Flask + JWT)

A secure web application built using **Flask (Python)** that demonstrates core web security concepts such as **authentication**, **authorization**, and **secure data storage**.  
This project is designed for learning and showcasing **secure coding practices** aligned with the **OWASP Top 10**.

---

## 🎯 Project Objective

To create a simple yet secure web application that implements:
- User authentication
- Authorization using JWT tokens
- Secure password storage
- SQL injection prevention

---

## 🚀 Features

- User **Registration** and **Login**
- **JWT-based Authentication**
- **Protected Routes** requiring authorization
- **Password Hashing** (no plaintext passwords)
- **Secure SQLite Storage**
- **SQL Injection Prevention**
- Minimal **frontend UI** for interaction
- Automatic database initialization

---

## 🛠️ Tech Stack

- **Backend:** Flask (Python)
- **Authentication:** JWT (Flask-JWT-Extended)
- **Password Security:** Werkzeug
- **Database:** SQLite
- **Frontend:** HTML (Jinja Templates)
- **Security Concepts:** OWASP Top 10

---

## 🧠 Skills Learned

- Web security fundamentals
- Secure coding practices
- Authentication & authorization
- JWT token handling
- Password hashing
- SQL injection prevention
- OWASP Top 10 awareness

---

## 📁 Project Structure
├── app.py # Main Flask application
├── requirements.txt # Python dependencies
├── database.db # SQLite database (auto-created, NOT pushed to GitHub)
├── templates/ # HTML templates
│ ├── index.html
│ ├── register.html
│ ├── login.html
│ └── profile.html
└── venv/ # Virtual environment

---

## ⚙️ Setup & Installation

### 🪟 Windows (PowerShell)

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
python app.py
