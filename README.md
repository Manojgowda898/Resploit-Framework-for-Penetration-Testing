# 🛡️ Resploit Framework for Penetration Testing (RFPT)

### 📖 Overview
**Resploit Framework for Penetration Testing (RFPT)** is a web-based educational framework designed to simulate and analyze real-world web vulnerabilities in a controlled environment.  
It provides a secure, hands-on platform for learning **ethical hacking**, **vulnerability assessment**, and **secure coding practices**.  

This project was developed as part of the **final-year engineering project** to demonstrate practical understanding of **web application security**.

---

## 🎯 Objectives
- Build a safe local platform for penetration testing practice.  
- Simulate common web vulnerabilities for educational exploration.  
- Understand exploit mechanisms and defensive countermeasures.  
- Encourage ethical hacking awareness and secure web development habits.

---

## ⚙️ Features
- Vulnerability modules including:
  - SQL Injection (SQLi)  
  - Cross-Site Scripting (XSS)  
  - Cross-Site Request Forgery (CSRF)  
  - File Inclusion  
  - Command Injection  
- Adjustable security levels — *Low*, *Medium*, *High*, *Impossible*.  
- Simple user interface with PHP-based backend.  
- Authentication system and configurable settings.  
- Self-contained setup through a browser-based configuration page.

---

## 🧩 Technologies Used

| Technology | Purpose |
|-------------|----------|
| **HTML, CSS, JavaScript** | Frontend design and interactivity |
| **PHP** | Backend scripting and logic |
| **MySQL** | Database management |
| **Apache (XAMPP/WAMP)** | Local web server for hosting the framework |

---

## 💻 Installation and Setup (Local Environment)

### Step 1: Prerequisites
Install one of the following:
- [XAMPP](https://www.apachefriends.org/index.html)  
  **or**
- [WAMP](https://www.wampserver.com/en/)

### Step 2: Project Setup
1. Download or clone this repository.  
2. Copy the project folder `RFPT` (your project directory) into:
C:\xampp\htdocs\
3. Start **Apache** and **MySQL** from your XAMPP/WAMP control panel.

### Step 3: Database Configuration
1. Open your browser and go to:
http://localhost/phpmyadmin
2. Create a new database named: dvwa
3. No manual import is needed — the setup page will automatically configure it.

### Step 4: Run the Project
1. Open:
http://localhost/RFPT/login.php
3. Default credentials:
Username: admin
Password: password


---

## 📂 Folder Structure
RFPT/
│
├── .github/ # GitHub-related configurations
├── config/ # Database and environment settings
├── database/ # Database schema and setup scripts
├── dvwa/ # Core backend logic and modules
├── external/ # External scripts and assets
├── hackable/ # Web application test files
├── tests/ # Security test modules
├── vulnerabilities/ # Vulnerability simulation files
│
├── about.php # About the project
├── index.php # Main home page
├── instructions.php # Usage instructions
├── login.php # User authentication page
├── logout.php # Logout script
├── php.ini # PHP configuration
├── phpinfo.php # PHP environment info
├── README.md # Project documentation
├── robots.txt # Search engine directives
├── SECURITY.md # Security notes
├── security.php # Security level settings
├── security.txt # Security metadata
└── setup.php # Application setup and initialization


---

## 🧠 Learning Outcomes
- Gain hands-on experience with **web security concepts**.  
- Learn how vulnerabilities are exploited and patched.  
- Understand secure coding practices and configuration management.  
- Build confidence in **penetration testing and ethical hacking**.  

---

## 📊 Project Details
**Project Title:** Resploit Framework for Penetration Testing (RFPT)  
**Project Type:** Final Year Major Project  
**Domain:** Cybersecurity / Web Application Security  
**Developed by:** **Manoj M**  
**Institution:** Dayananda Sagar College of Engineering, Bangalore  

---

## ⚠️ Disclaimer
This project is intended **strictly for educational and research purposes only**.  
It must **not** be used for unauthorized or illegal activities.  
The author assumes no responsibility for misuse of this software.

---

## 📘 License
This project is developed as part of an academic research requirement.  
You are free to use or modify it for **learning and personal study** purposes.

---


