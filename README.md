# 🏥 Prescripto — Doctor Appointment Booking System

A full-stack **MERN (MongoDB, Express, React, Node.js)** application for managing doctor appointments with multi-role authentication (Patient, Doctor, Admin), real-time slot booking, and online payment integration.

---
🌐 Live Demo

👉 Live link(render): https://app-frontend-qxlr.onrender.com/
👉 Admin Panel: https://app-admin-dfrl.onrender.com/

---

## 🚀 Live Overview

Prescripto is a scalable healthcare web application designed to streamline the process of booking and managing doctor appointments. It supports dynamic scheduling, role-based dashboards, and secure payment processing.

---

## ✨ Key Features

### 👤 Patient Module

* Register/Login securely
* Browse doctors by specialization
* Book appointments based on real-time availability
* Make online payments using Razorpay
* View and manage booked appointments

### 🩺 Doctor Module

* Secure login dashboard
* View scheduled appointments
* Update availability status
* Cancel or manage bookings
* Track earnings
* Update profile details

### 🛠️ Admin Module

* Add/manage doctors
* Monitor all appointments
* Manage system-level operations
* Control doctor availability and profiles

---

## ⚙️ Tech Stack

### Frontend

* React.js (Vite)
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### Authentication

* JWT (JSON Web Tokens)
* Role-based access (Admin / Doctor / User)

### Payment Integration

* Razorpay

---

## 🧠 Core Functionalities

* 📅 Dynamic slot generation based on current time
* 🔄 Real-time appointment updates
* 🔐 Multi-level authentication system
* 💳 Secure online payment workflow
* 📊 Dashboard analytics for doctors and admin
* ⚡ Optimized API communication

---

## 📂 Project Structure

```
App/
│
├── admin/          # Admin Panel (React)
├── frontend/       # User/Patient Frontend (React)
├── backend/        # Node.js + Express Server
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sudharsantp/App.git
cd App
```

---

### 2️⃣ Setup Backend

```bash
cd backend
npm install
npm start
```

Create `.env` file in backend:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
RAZORPAY_KEY_ID=your_key
RAZORPAY_SECRET=your_secret
```

---

### 3️⃣ Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

---

### 4️⃣ Setup Admin Panel

```bash
cd ../admin
npm install
npm run dev
```

---

## 🌐 Application Flow

```
User → React Frontend → Express API → MongoDB Atlas → Response → UI Render
```

---

## ⚠️ Known Issues / Notes

* Initial loading delay may occur due to MongoDB Atlas free-tier cold start
* Ensure IP is whitelisted in MongoDB Atlas (0.0.0.0/0 for development)

---

## 🚧 Future Improvements

* Notification system (Email/SMS)
* Advanced doctor search & filters
* Appointment reminders
* Scalability improvements with caching
* Deployment (Docker + CI/CD)

---

## 👨‍💻 Author

**T P Sudharsan**

* GitHub: https://github.com/sudharsantp
* Email: [sudhu4007@gmail.com](mailto:sudhu4007@gmail.com)

---
