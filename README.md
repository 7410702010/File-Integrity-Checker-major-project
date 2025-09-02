# 🔐 Secure Login System using Python & Flask

## 📌 Objective
A simple, secure web login system built with **Flask, SQLite, and bcrypt**.  
This project demonstrates:
- Secure password storage (hashing)
- User signup/login with validation
- SQL Injection & XSS prevention
- Session-based authentication
- Examples of both successful and failed login attempts

---

## ⚙️ Features
- **User Signup & Login** with form validation
- **Password Hashing** using `bcrypt` (or `pbkdf2:sha256` fallback)
- **Input Validation**:
  - Username: letters, numbers, underscore only (`3-20 chars`)
  - Password: at least 8 chars, must include uppercase, lowercase, digit, symbol
  - Email format check
- **Database Security**: Prepared statements to prevent SQL Injection
- **XSS Protection**: Auto-escaping + strict Content-Security-Policy
- **Sessions**: Secure cookies (`HttpOnly`, `SameSite`)
- **Tests/Demo**: Includes a script that demonstrates successful & failed login attempts

---

## 🛠️ Tech Stack
- **Backend**: Python 3, Flask
- **Database**: SQLite
- **Security**: bcrypt (hashing), WTForms-style manual validation
- **Frontend**: Jinja2 templates, simple Bootstrap CSS

---

## 🚀 Installation & Usage

### 1️⃣ Clone or Download
```bash
git clone https://github.com/your-username/secure-flask-login.git
cd secure-flask-login
