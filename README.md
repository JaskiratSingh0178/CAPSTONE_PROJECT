# 🎟️ Event Booking & Reservation System (MERN Stack)

A full-stack **Event Booking & Reservation System** built using the **MERN stack (MongoDB, Express, React, Node.js)**.  
This project supports **role-based authentication (Admin & User)**, event management, booking system, and a modern UI.

---

## 🌐 Live Demo
👉 https://booking-app-a4jc.onrender.com/

---

## 📌 Features

### 👤 User Features
- Register & Login authentication
- View all available events
- Filter events by date
- View upcoming & past events
- Book event with payment simulation 💳
- Cancel bookings
- View personal bookings

---

### 🛠️ Admin Features
- Admin login access
- Add new events
- Delete events
- Manage event details (date, time, seats, price)

---

### ⚙️ General Features
- JWT Authentication 🔐
- REST API integration
- MongoDB Atlas database ☁️
- Responsive modern UI
- Single deployment (frontend + backend)
- Live hosted on Render

---

## 🏗️ Tech Stack

### Frontend
- React.js
- Axios
- React Router DOM
- CSS (Custom UI)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- bcrypt.js

### Deployment
- Render (Single Service Deployment)
- MongoDB Atlas

---

## 📁 Project Structure

booking-system/
│
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── server.js
│ └── package.json
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── pages/
│ │ ├── services/
│ │ ├── App.js
│ │ └── App.css
│ ├── package.json
│ └── build/
│
├── .gitignore
└── README.md


---

## 🚀 Installation & Setup

### 1️⃣ Clone the repository
bash
git clone https://github.com/your-username/your-repo-name.git
cd booking-system

## 2️⃣ Setup Backend

cd backend
npm install

## 3️⃣ Setup Frontend

cd frontend
npm install
npm start

## 🌍 Deployment (Render)
