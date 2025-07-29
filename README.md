# 🏠 RENTAL HOME

**RENTAL HOME** is a secure authentication-based web application designed with modular architecture. It includes user login/signup functionality using PHP and integrates mailing support with PHPMailer. The project follows clean code practices and is ready for production deployment.

---

## 🚀 Features

- ✅ User Registration & Login
- 🔐 Secure Authentication with Sessions
- 📧 Email Notifications using PHPMailer
- 🗃️ Configurable Project Structure
- 🌐 Docker Support (optional, ignored in repo)
- 💡 Clean & Maintainable Codebase

---

## 📁 Folder Structure

grih-chhaya/
├── auth/ # Authentication logic
│ ├── login.php
│ └── register.php
├── config/ # DB & site config (ignored from repo)
├── PHPMailer/ # Email library (ignored from repo)
├── index.php # Homepage or redirect logic
├── .gitignore # Files/folders excluded from Git
├── README.md # This file
└── ... # Other resources



---

## ⚙️ Technologies Used

- PHP (Core)
- PHPMailer
- HTML/CSS/JS
- MySQL
- Docker (for local setup)
- Git & GitHub

---

## 🧾 Setup Instructions

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/grih-chhaya_a_rental_app.git
   cd grih-chhaya

   Install dependencies

Configure your local PHP and MySQL setup.

Add your database credentials in /config/db.php.

PHPMailer

Add PHPMailer files under /auth/PHPMailer/ if not already there.

Configure SMTP settings.

Database

Import grih_chhaya.sql (if provided) in phpMyAdmin or CLI.

📂 Ignored from Repository
These directories are added in .gitignore to keep sensitive or heavy files out of version control:
/auth/PHPMailer/
/config/


👨‍💻 Author
Pawan Kumar Sharma
