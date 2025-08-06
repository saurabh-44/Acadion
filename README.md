# 🎓 Acadion – Full-Stack EdTech Platform

🚀 Live Demo: [acadion-ashy.vercel.app](https://acadion-ashy.vercel.app/)

**Acadion** is a full-fledged EdTech platform built with the MERN stack. It empowers users to create, consume, and manage educational content through a seamless and interactive UI. Whether you're a student or an instructor, Acadion provides all the tools needed for digital learning and course management.

## ✨ Features

### 👨‍🎓 For Students:
- Browse and enroll in courses
- Add courses to wishlist or cart
- Consume video content and course materials
- Track learning progress and update profile

### 👨‍🏫 For Instructors:
- Create and manage courses with pricing
- Upload videos and written content (Markdown-supported)
- View insights on engagement
- Manage personal and course profiles

### 🧾 General Platform Features:
- Secure authentication (JWT + Bcrypt)
- Cloud-based media storage via Cloudinary
- Razorpay integration for payments
- Fully responsive UI (Tailwind CSS + React)
- Role-based dashboard and access control

---

## 🧠 Introduction

**Acadion** is designed to make learning and teaching easier. It provides a complete suite of tools for:

- Learners to discover and consume content
- Instructors to showcase their skills and monetize courses
- Admins to manage users and content at scale

The platform combines an intuitive UI with robust backend APIs to support real-time learning and content management.

---

## 🛠️ Tech Stack

| Layer        | Tech Used                      |
|--------------|--------------------------------|
| Frontend     | React.js, Tailwind CSS, Redux  |
| Backend      | Node.js, Express.js            |
| Database     | MongoDB, Mongoose              |
| Auth & Sec   | JWT, Bcrypt                    |
| Media        | Cloudinary                     |
| Payments     | Razorpay API                   |
| Deployment   | Vercel (Frontend), Render (Backend) |

---

### 📁 Frontend (React)
- Fully responsive UI
- Student & instructor dashboards
- State management via Redux
- Integration with backend APIs

### ⚙️ Backend (Node + Express)
- RESTful APIs for all operations
- Modular controller-service-DB structure
- Handles auth, course creation, payments, etc.

### 🗃️ Database (MongoDB)
- Models for User, Course, Category, Section, Subsection, Ratings
- Schemas managed via Mongoose

---

## 📦 Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/acadion.git

# 2. Navigate to project root
cd acadion

# 3. Install backend dependencies
npm install

# 4. Navigate to client and install frontend dependencies
cd client
npm install
```

## 🚀 Usage

```bash
# 1. Start backend server
npm run start

# 2. In another terminal, start frontend
cd client
npm run start
