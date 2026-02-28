🏛 Govt Complaint Portal – Frontend (React)

The Govt Complaint Portal Frontend is a React-based web application that enables citizens of Uttar Pradesh to register, login, and submit government complaints district-wise (75 districts) for issues such as water supply, electricity, and other public services.

This frontend communicates with a deployed Java Servlet-based REST API backend.

🌐 Live Application

Frontend (React - Hosted on Render):
👉 https://govt-project-kpaw.onrender.com

Backend API (Java Servlets - Hosted on Render):
👉 https://complaint-portal-xfaa.onrender.com

🚀 Features

👤 User Registration (Signup)

🔐 Secure Login Authentication

📝 Submit Complaint Form

📍 District-wise Complaint Submission (All 75 Districts of UP)

🏷 Complaint Categories (Water, Electricity, etc.)

🔄 REST API Integration

📱 Responsive Design

⚡ Optimized Production Build

🛠️ Tech Stack
🔹 Frontend

React.js

JavaScript (ES6+)

HTML5

CSS3

Axios (API communication)

React Router (Navigation)

🔹 Backend (Connected API)

Java (Servlets)

JDBC

MySQL

HikariCP

Gson

🔹 Deployment

Render (Frontend & Backend hosted separately)

⚙️ Local Development Setup
1️⃣ Clone Repository
git clone https://github.com/Ashwani5977/govt-complain-project-frontend-.git
cd govt-complaint-frontend
2️⃣ Install Dependencies
npm install
3️⃣ Configure Backend URL

Inside your API configuration file (example: src/api.js), ensure:

const BASE_URL = "https://complaint-portal-xfaa.onrender.com";
4️⃣ Start Development Server
npm start

The app will run at:

http://localhost:3000
🏗 Application Architecture
React Frontend
   ⬇ REST API Calls (Axios)
Java Servlet Backend
   ⬇ JDBC
MySQL Database
📂 Project Structure
src/
 ├── components/
 ├── pages/
 ├── services/
 ├── api.js
 ├── App.js
 └── index.js
🎯 Project Objective

The objective of this frontend application is to provide a simple, accessible, and efficient digital platform for citizens to register complaints and improve communication with government authorities.

🔮 Future Enhancements

Admin Panel UI

Complaint Status Tracking

User Profile Management

Role-Based Access UI

Analytics Dashboard

UI/UX Enhancements

💡 Project Highlights

✔ Full-Stack Integration

✔ Production Deployment

✔ REST API Communication

✔ Authentication System

✔ Real-world Government Complaint Use Case
