# 📚 Learnhub – Online Learning Platform using MERN

An online learning platform (OLP) that empowers students, teachers, and admins through seamless content delivery, course management, and certification using the MERN stack (MongoDB, Express.js, React.js, Node.js).

---

## 🧠 Team Details

- **Team ID:** LTVIP2025TMID54785  
- **Team Leader:** Madduri Vara Prasad  
- **Team Members:**  
  - Nandyala Meghana  
  - Phaneendra Gangadi  
  - Velagala Maheswari  

---

## 🌐 Live Demo & Code

- 🔗 [Project Drive Folder (Code & Resources)](https://drive.google.com/drive/folders/1d7N-lwCb5QvT7ERs9AeqnU_4mmaSCNNv?usp=share_link)  
- 🎥 [Demo Video](https://drive.google.com/file/d/1ehubxqoLt0Jc3J71MoKl7zR-WagaS3jy/view?usp=share_link)

---

## 🚀 Features

### 👩‍🏫 Teacher
- Add or remove courses.
- Create and manage course sections.

### 👨‍🎓 Student
- Register and log in to the platform.
- Enroll in free and paid courses.
- Resume progress and complete courses at their own pace.
- Download certificates after completion.
- Filter courses by name and category.

### 🛠️ Admin
- Manage all users (teachers and students).
- Modify or delete any course.
- Monitor student enrollments and platform activity.

---

## 🛠️ Tech Stack

### Frontend
- React.js (Vite)
- Bootstrap, Material UI, MDB React UI Kit, Ant Design
- Axios for API communication

### Backend
- Node.js (node_modules are not included in the drive due to large storage)
- Express.js
- MongoDB + Mongoose
- JWT for authentication
- Multer for file handling
- CORS, dotenv, bcryptjs

---

## ⚙️ Installation Guide

### 🔧 Prerequisites

- Node.js and npm ([Install here](https://nodejs.org/en/download/))
- MongoDB ([Install here](https://www.mongodb.com/try/download/community))
- Git

---

### 📦 Setup Instructions

```bash
# download zip file from drive and unzip it
cd Learnhub

# Install backend dependencies
cd code/backend
npm install

# Start backend server
npm start
# Server runs at: http://localhost:8000

# Install frontend dependencies
cd ../frontend
npm install

# Start frontend (Vite) server
npm run dev
# App runs at: http://localhost:5173
