# 🌐 TaskFlow Pro – Real-Time Project Management Platform

## 📌 Project Description

TaskFlow Pro is a full-stack collaborative project management web application inspired by Trello and Asana. It allows teams to manage projects efficiently using Kanban boards, tasks, comments, notifications, and real-time collaboration features.

The platform is built using React.js, Node.js, Express.js, MySQL, Sequelize ORM, and Socket.io with a scalable clean architecture.

---

# 🚀 Features

## 🔐 Authentication & User Management

* User registration and login system
* JWT Authentication with Refresh Tokens
* Password hashing using bcrypt
* Role-Based Access Control (RBAC)
* Secure protected routes
* User profiles with:

  * Name
  * Email
  * Avatar
  * Bio
* Update profile functionality

---

## 📁 Project Management System

* Create and manage projects
* Invite team members via email/link
* Assign project roles:

  * Admin
  * Member
* Project dashboard with team collaboration

---

## 📋 Kanban Board System

* Multiple boards inside projects
* Drag-and-drop board reordering
* Create, update, and delete boards
* Real-time board synchronization

---

## ✅ Task Management

* Create, edit, and delete tasks
* Assign tasks to users
* Task priorities:

  * Low
  * Medium
  * High
  * Critical
* Due dates support
* Labels/tags support
* Drag-and-drop tasks between boards
* Real-time task updates

---

## 💬 Comments System

* Threaded comments on tasks
* @Mention users
* Real-time comments using Socket.io
* Timestamp support

---

## 🔔 Notifications System

* Real-time notifications
* Notifications for:

  * Task assignment
  * Task updates
  * New comments
  * Mentions
* Mark notifications as read/unread

---

## ⚡ Real-Time Features

* Live task updates
* Live comments
* Online presence indicator
* Instant notifications
* Real-time collaboration using Socket.io

---

# 🛠️ Tech Stack

## Frontend

* React.js
* Tailwind CSS
* Zustand
* React Router DOM
* Axios
* dnd-kit

## Backend

* Node.js
* Express.js
* MySQL (XAMPP)
* Sequelize ORM

## Authentication & Security

* JWT Authentication
* bcrypt
* Joi Validation
* Helmet
* Express Rate Limit

## Real-Time

* Socket.io

---

# 📱 Responsive Design

The application is fully responsive and optimized for:

* 📱 Mobile Devices
* 📲 Tablets
* 💻 Desktop Screens

---

# 🏗️ Clean Architecture

The project follows a scalable clean architecture:

```bash
Controllers → Services → Repositories → Database
```

---

# 📂 Project Structure

```bash
TaskFlow-Pro/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── repositories/
│   │   ├── models/
│   │   ├── middleware/
│   │   ├── routes/
│   │   ├── sockets/
│   │   ├── validations/
│   │   └── utils/
│   │
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── hooks/
│   │   ├── services/
│   │   └── routes/
│   │
│   └── package.json
│
├── database/
├── screenshots/
├── README.md
└── .env
```

---

# 🗄️ Database Tables

* users
* projects
* project_members
* boards
* tasks
* task_assignments
* comments
* notifications

---

# 🔌 REST API Structure

## Base URL

```bash
/api/v1
```

## Main Routes

```http
POST   /auth/register
POST   /auth/login
POST   /auth/logout

GET    /projects
POST   /projects

GET    /boards
POST   /boards

GET    /tasks
POST   /tasks

POST   /comments
GET    /notifications
```

---

# ⚙️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/your-username/taskflow-pro.git
```

## Navigate Into Project

```bash
cd taskflow-pro
```

## Install Dependencies

```bash
npm install
```

## Start Backend Server

```bash
cd backend
npm run dev
```

## Start Frontend

```bash
cd frontend
npm run dev
```

---

# 🔑 Environment Variables

Create a `.env` file in the backend directory:

```env
PORT=5000

DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=
DB_NAME=taskflow_pro

JWT_ACCESS_SECRET=your_access_secret
JWT_REFRESH_SECRET=your_refresh_secret

CLIENT_URL=http://localhost:5173
```

---

# 🗄️ Database Setup

1. Open XAMPP
2. Start Apache & MySQL
3. Open phpMyAdmin
4. Create database:

```sql
CREATE DATABASE taskflow_pro;
```

5. Run Sequelize migrations

```bash
npx sequelize-cli db:migrate
```

---

# 📸 Screenshots

<img width="1920" height="850" alt="Screenshot (233)" src="https://github.com/user-attachments/assets/f05000af-cba6-4341-a948-d54e21d5d5bd" />
<img width="1920" height="900" alt="Screenshot (234)" src="https://github.com/user-attachments/assets/a0c74366-9efb-49f3-98a7-0325c18b775c" />
<img width="1920" height="867" alt="Screenshot (235)" src="https://github.com/user-attachments/assets/9be5e7a2-c379-4f55-ab56-96789e7ff8f1" />
<img width="1920" height="843" alt="Screenshot (236)" src="https://github.com/user-attachments/assets/0a769d26-dff0-4662-a827-89d60aff768d" />
<img width="1920" height="806" alt="Screenshot (237)" src="https://github.com/user-attachments/assets/a90f5b2f-cb9c-4764-889b-ab1d9c7ce392" />
<img width="773" height="873" alt="Screenshot (238)" src="https://github.com/user-attachments/assets/eef3a198-1144-4162-b2ab-89174bb24221" />



---


---

# 👨‍💻 Author

Your Name
GitHub: (https://github.com/I-AM-BATOT)

---

# 📌 About

TaskFlow Pro is a modern SaaS-style project management platform designed with scalability, maintainability, and real-time collaboration in mind.

---

# 📊 Languages & Technologies

* JavaScript
* React.js
* Node.js
* Express.js
* MySQL
* Tailwind CSS
* Socket.io

---

# ⭐ Resources

* README
* API Documentation
* Database Schema
* Postman Collection

---

# ❤️ Conclusion

TaskFlow Pro is a production-ready collaborative project management application built with modern full-stack technologies and clean architecture principles.
