# 📝 Secure Blog API

A **Secure Blog REST API** built with **Express.js**, implementing **JWT Authentication**, **role-based access control**, and following secure coding practices.  
This project was developed as part of my **TechNest Virtual Internship**.

---

## 🚀 Features

- 🔐 **Authentication & Authorization**
  - Register & Login with JWT
  - Password hashing using **bcryptjs**
  - Protected routes with middleware
  - Role-based access control

- 🛡️ **Security**
  - JWT Authentication
  - Rate Limiting
  - Input validation
  - Security headers with **Helmet**
  - **CORS Protection**

- 📚 **Blog System**
  - Create, read, update, delete posts
  - Get user’s posts
  - Popular tags
  - Pagination & search support

- ⚡ **Tech Stack**
  - Node.js + Express.js
  - MongoDB + Mongoose
  - JWT + bcryptjs
  - Helmet, CORS, Express-rate-limit

---

## 📂 Project Structure
.
├── src
│ ├── config/ # Database & config files
│ ├── controllers/ # API route controllers
│ ├── middleware/ # JWT auth, error handling, role-based access
│ ├── models/ # Mongoose schemas
│ ├── routes/ # API routes
│ └── utils/ # Helper functions
└── server.js # Entry point
