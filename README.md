# 🚀 InterviewIQ – AI-Powered Interview Preparation SaaS
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase)
![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=for-the-badge&logo=razorpay)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render)

<p align="center">
  <strong>A production-ready AI-powered Interview Preparation SaaS Platform built with the MERN Stack.</strong>
</p>

<p align="center">
  Generate personalized interview questions, practice technical & HR interviews, receive AI-powered feedback, and manage premium access through a secure credit-based system.
</p>

<p align="center">
  <a href="https://interview-iq-rnmu.onrender.com/" target="_blank"><strong>🌐 Live Demo</strong></a> •
  <a href="https://github.com/Dipanshuk1/InterviewIQ" target="_blank"><strong>📂 GitHub</strong></a>
</p>

---

## 📖 Overview

InterviewIQ is a full-stack AI-powered Interview Preparation platform designed to help job seekers improve their interview skills through personalized AI-generated interview sessions.

Users can upload their resumes, receive customized technical and HR interview questions, practice interviews, obtain intelligent AI feedback, and purchase credits using Razorpay to unlock premium AI features.

The project follows a modern SaaS architecture with secure authentication, payment integration, RESTful APIs, and cloud deployment.

---

# ✨ Features

### 👤 Authentication

- Firebase Google Authentication
- Secure JWT Authorization
- Protected Routes
- User Profile Management

### 📄 Resume Management

- Upload Resume (PDF)
- Secure File Storage
- Resume Processing

### 🤖 AI Interview Engine

- AI-generated Interview Questions
- Technical Interview Practice
- HR Interview Practice
- Personalized Interview Sessions

### 📊 AI Feedback

- Intelligent Interview Feedback
- Performance Suggestions
- Improvement Recommendations

### 💳 SaaS Features

- Credit-Based Access System
- Premium Feature Unlock
- Razorpay Payment Gateway
- Payment Verification

### 🎨 Frontend

- Fully Responsive Design
- Modern Dashboard
- Framer Motion Animations
- Professional UI/UX

### ☁️ Deployment

- Production Ready
- Render Deployment
- Environment Configuration

---

# 🛠 Tech Stack

## Frontend

- React.js
- React Router
- Framer Motion
- Axios
- CSS / Tailwind CSS *(if applicable)*

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

## Authentication

- Firebase Google Authentication
- JWT

## Payment

- Razorpay

## Deployment

- Render

---

# 🏗 Project Architecture

```
Client (React.js)
        │
        ▼
Express REST APIs
        │
 ┌──────┴────────┐
 │               │
 ▼               ▼
MongoDB      Firebase Auth
        │
        ▼
 AI Service
        │
        ▼
 Razorpay Payment Gateway
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Dipanshuk1/InterviewIQ.git

cd InterviewIQ
```

---

## Install Frontend

```bash
cd client

npm install

npm run dev
```

---

## Install Backend

```bash
cd server

npm install

npm run dev
```

---

# 🔐 Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=5000

MONGO_URI=

JWT_SECRET=

FIREBASE_API_KEY=

FIREBASE_PROJECT_ID=

RAZORPAY_KEY_ID=

RAZORPAY_SECRET=

AI_API_KEY=
```

---

# 📂 Folder Structure

```
InterviewIQ/

│

├── client/

│   ├── components/

│   ├── pages/

│   ├── hooks/

│   ├── context/

│   └── assets/

│

├── server/

│   ├── controllers/

│   ├── routes/

│   ├── middleware/

│   ├── models/

│   ├── utils/

│   ├── config/

│   └── uploads/

│

└── README.md
```

---

# 🔥 Core Functionalities

- User Authentication
- Resume Upload
- AI Resume Analysis
- Personalized Interview Questions
- Technical Interview Practice
- HR Interview Practice
- AI Feedback
- Credit Management
- Razorpay Integration
- Secure REST APIs
- Responsive Dashboard
- Cloud Deployment

---

# 📚 What I Learned

During this project I gained practical experience in:

- Building production-ready MERN applications
- Designing scalable REST APIs
- Authentication & Authorization
- SaaS Architecture
- AI API Integration
- Payment Gateway Integration
- MongoDB Database Design
- Cloud Deployment
- Secure Backend Development
- Frontend Performance Optimization

---

# 🚀 Future Improvements

- Voice-based AI Interviews
- AI Avatar Interviewer
- Interview History Analytics
- Resume Score Analysis
- Coding Assessment Module
- Email Notifications
- Admin Dashboard
- Subscription Plans
- Interview Recording
- Multi-language Support


Example:

- Login Page
- Dashboard
- Resume Upload
- AI Questions
- AI Feedback
- Razorpay Checkout
- User Profile

---

# 👨‍💻 Author

**Dipanshu Kumar**

LinkedIn

https://linkedin.com/in/contactdipanshukumar1

GitHub

https://github.com/Dipanshuk1

Email

dipanshu.cse2026@gmail.com

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository.

It motivates me to build more production-ready full-stack applications.

---

## 📄 License

This project is licensed under the MIT License.
