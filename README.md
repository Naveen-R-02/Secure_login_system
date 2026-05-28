# Secure Login System

A secure web-based authentication system developed using Flask, SQLite, and Bcrypt. The application provides user registration, secure login, password hashing, session management, and logout functionality while following basic cybersecurity best practices.

## Features

- User Registration
- Secure Login Authentication
- Bcrypt Password Hashing
- SQLite Database Integration
- Session Management
- Logout Functionality
- SQL Injection Protection using SQLAlchemy ORM
- User Statistics Dashboard

## Technologies Used

- Python
- Flask
- SQLite
- Flask-Bcrypt
- Flask-Login
- Flask-SQLAlchemy
- HTML
- CSS

## Project Structure

```bash
secure_login_system/
│
├── app.py
├── users.db
│
├── templates/
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
│
├── static/
│   └── style.css
```

## Run the Project

Install dependencies:

```bash
pip install flask flask-bcrypt flask-sqlalchemy flask-login
```

Run the application:

```bash
python app.py
```

Open in browser:

```bash
http://127.0.0.1:5000
```

## Security Features

- Passwords stored as bcrypt hashes
- Session-based authentication
- Unique username and email validation
- SQL Injection protection through SQLAlchemy ORM
- Secure login and logout workflow

## Author

**Naveen R**  
Cyber Security Intern @ Thiranex
