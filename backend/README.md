# Backend – Multi-Tenant SaaS Platform

This is the **backend API** for the **Multi-Tenant SaaS Project & Task Management System**.  
It is built using **Node.js, Express.js, PostgreSQL**, and follows **secure multi-tenant architecture** with proper data isolation, authentication, and authorization.

The backend exposes RESTful APIs for tenant management, user management, projects, and tasks, and is fully containerized using **Docker**.

---

## 🚀 Features

- Multi-tenant architecture with **strict tenant data isolation**
- JWT-based authentication (24-hour expiry)
- Role-based access control (RBAC)
  - Super Admin
  - Tenant Admin
  - User
- Subscription plan enforcement (Free / Pro / Enterprise)
- Secure password hashing using **bcrypt**
- PostgreSQL database with migrations & seed data
- Audit logging for critical actions
- Dockerized backend with automatic DB initialization
- Health check endpoint for monitoring

---

## 🧱 Tech Stack

| Layer        | Technology |
|-------------|-----------|
| Runtime     | Node.js (ES Modules) |
| Framework   | Express.js |
| Database    | PostgreSQL |
| Auth        | JWT |
| Security    | bcrypt |
| ORM / DB    | pg (node-postgres) |
| Container   | Docker |
| API Docs    | Postman / Swagger (optional) |

---

## 📂 Project Structure

