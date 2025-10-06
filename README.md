<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Kavinmano/Roxiler-Systems-Task">
    <img src="public/store3d.jpg" alt="Logo" width="120" height="100">
  </a>

  <h2 align="center">🛍️ Store Rating WebApp</h2>

  <p align="center">
    A full-stack web application that allows users to rate and review stores.<br/>
    Built for the <strong>Roxiler Systems Task</strong> using modern technologies.
    <br /><br />
    <a href="https://github.com/Kavinmano/Roxiler-Systems-Task"><strong>Explore the repo »</strong></a>
    <br /><br />
  </p>
</div>

---

## 🚀 Overview

**Store Rating WebApp** is a role-based review system that enables users to rate stores, while administrators and store owners manage and view store performance through interactive dashboards.

---

## ⚙️ Features

### 👑 System Administrator
- Add new **stores**, **normal users**, and **admin users**.
- View **dashboard statistics**:
  - Total users  
  - Total stores  
  - Total ratings submitted
- View and manage:
  - ✅ Store list with Name, Email, Address, and Rating  
  - ✅ User list with Name, Email, Address, and Role
- Apply filters by **Name**, **Email**, **Address**, or **Role**.
- View detailed user info (if Store Owner → shows Rating).
- Secure **logout** functionality.

---

### 🙍 Normal User
- **Sign up** and **log in** securely.
- **Update password** after login.
- **Search** stores by Name or Address.
- View:
  - 🏪 Store Name  
  - 📍 Address  
  - ⭐ Overall Rating  
  - 🧍 User’s Submitted Rating
- Submit or modify **ratings (1–5)** for stores.
- Secure **logout** functionality.

---

### 🏪 Store Owner
- Secure **login** and **password update**.
- Dashboard includes:
  - List of **users** who rated the store.
  - Average **store rating**.
- Secure **logout** functionality.

---

## 🧾 Form Validations

| Field | Validation Rules |
|-------|------------------|
| **Name** | 20–60 characters |
| **Address** | Max 400 characters |
| **Password** | 8–16 characters, at least one uppercase letter and one special character |
| **Email** | Must follow standard email format |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | React.js, Redux, Axios, TailwindCSS |
| **Backend** | Spring Boot (Java) |
| **Database** | MySQL |
| **Authentication** | JWT (JSON Web Token) |
| **Deployment** | Netlify (Frontend) / Spring Boot Server (Backend) |

---

## 🧩 Project Structure

