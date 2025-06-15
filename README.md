# Authentication_with_Cookies_Sessions_Passport.js
Authentication, Underlined — using Sessions, Cookies, and Passport.js


# Session Auth with Passport and PostgreSQL

A simple user authentication system built with **Node.js**, **Express**, **Passport.js**, and **PostgreSQL**. It supports session-based login and user registration using **bcrypt** for password hashing and **cookies** for session management.

## 🔐 Key Features

- User registration and login system
- Password hashing with `bcrypt`
- Persistent login using `express-session`
- Authentication handled by `passport` and `passport-local`
- PostgreSQL as the database
- Session storage in memory (for now)

---

## 🧱 Tech Stack

| Layer         | Tech                        |
|--------------|-----------------------------|
| Server       | Node.js + Express           |
| Auth         | Passport.js (`local` strategy) |
| Database     | PostgreSQL                  |
| Passwords    | bcrypt                      |
| Sessions     | express-session + cookies   |
| Templating   | EJS                         |

---

## 📌 Routes Overview

### 📖 Overview

| Section                | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🎯 Project Goal         | Implement a user authentication system using sessions, cookies, and Passport.js |
| 🧰 Key Technologies      | Node.js, Express, Passport.js, PostgreSQL, bcrypt                          |
| 🧪 Authentication Type  | Session-based authentication using `passport-local`                        |
| 🔐 Password Handling     | Passwords are hashed using `bcrypt` before being stored in the database     |
| 🗂️ Session Storage       | Managed by `express-session` and stored in browser cookies                 |
| 🧭 Main Routes           | `/register`, `/login`, `/secrets`, `/logout`                              |
| 📦 Project Structure     | Clean separation between routing, logic, and templates                     |
| ✅ Access Control        | Protected routes with `req.isAuthenticated()`                              |
| 📚 Suitable For         | Learning authentication, practice projects, quick auth setup               |
| 🌍 User Interface       | Built with EJS templates for registration, login, and protected content    |


<img width="728" alt="3 1" src="https://github.com/user-attachments/assets/aba43fb6-0d74-401e-a87b-f75511117c74" />


