# 🔐 Secure Software Project - Basic Software Security Practices for Beginners

This is an educational full-stack web application that introduces beginner developers to **essential software security practices**. It simulates a secure login and registration process, while also providing awareness about phishing attacks—all built using Node.js, Express, and SQLite.

---

🧠 Project Overview

This project demonstrates how to build safer software by applying foundational security principles from the start. It focuses on:

- **Secure password storage** with hashing and salting using `bcrypt`
- **SQL injection protection** through parameterized queries
- **Phishing awareness training** via front-end examples and tips

---

🛠️ Tech Stack

| Layer     | Technology |
|-----------|------------|
| Frontend  | HTML, CSS |
| Backend   | Node.js, Express.js |
| Database  | SQLite |
| Security  | bcrypt, input validation, parameterized SQL |

---

🔐 Security Concepts Demonstrated

 ✅ 1. Secure Password Management
- Passwords are **never stored in plaintext**.
- Each password is **hashed with a unique salt** using `bcrypt`.
- This protects against brute-force attacks and rainbow tables.

 ✅ 2. SQL Injection Prevention
- All SQL queries are written with **parameterized placeholders ()**, not string concatenation.
- This makes the database immune to injection attacks like `' OR 1=1 --`.

 ✅ 3. Phishing Awareness
- The front-end includes a **Phishing Red Flags** section that:
  - Educates users about suspicious URLs, urgent email language, and grammar issues
  - Demonstrates social engineering awareness in a non-technical way

---
