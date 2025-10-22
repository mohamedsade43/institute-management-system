🏫 Institute Management System (MVP)

A simple, clean, and scalable Institute Management System built using:

Frontend: HTML, Vanilla CSS, JavaScript

Backend: Node.js, Express.js, MongoDB

🎯 Purpose: To manage students, courses, attendance, and payments efficiently for an offline institute as an admin using for online access .
This is the MVP (Minimum Viable Product) version — focused on essential features only.

📁 Project Structure
institute-management-system/
│
├── frontend/              # Frontend (HTML, CSS, JS)
│   ├── index.html         # Dashboard / Homepage
│   ├── students.html
│   ├── courses.html
│   ├── attendance.html
│   ├── payments.html
│   ├── reports.html
│   ├── settings.html
│   ├── css/
│   ├── js/
│   ├── assets/
│   └── components/
│
├── backend/               # Backend (Node.js + Express + MongoDB)
│   ├── server.js
│   ├── config/
│   ├── models/
│   ├── routes/
│   └── controllers/
│
└── shared/                # Shared utilities (optional)
    ├── utils/
    ├── constants/
    └── validation/

🚀 Features (MVP)

✅ Admin Dashboard – Overview of students, attendance, payments, and courses
✅ Student Management – Add, view, edit, delete student records
✅ Course Management – Create and manage courses
✅ Attendance Tracking – Mark present/absent students
✅ Payment Records – Manage and track fee payments
✅ Reports – Simple visual reports for attendance and payments
✅ Single Admin User – Basic login and access control

🧠 Tech Stack
Layer	Technology
Frontend	HTML, Vanilla CSS, JavaScript
Backend	Node.js, Express.js
Database	MongoDB
Version Control	Git + GitHub
Design Tools (optional)	Figma, Draw.io
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/mohamedsade43/institute-management-system.git
cd institute-management-system

2️⃣ Setup Backend
cd backend
npm install
npm start


Make sure MongoDB is running locally or provide a connection string in .env.

3️⃣ Setup Frontend

Just open frontend/index.html in your browser — no build tools required.

🌐 Folder Usage Overview
Folder	Description
frontend/	All static files: HTML, CSS, JS, and assets
backend/	Node.js + Express server code
shared/	Utility functions and constants shared between frontend & backend
📈 Future Improvements (Phase 2 – MERN Upgrade)

Implement full authentication (JWT)

Use React for frontend

Add API-based communication between frontend & backend

Include file uploads (student photos, receipts)

Create printable and exportable reports

Deploy to cloud (Render, Vercel, or Railway)

👨‍💻 Author

Name: [Mohamed Abdirizak Mohamed]
Role: Founder & Developer
Email: [mohamedsade@gmail.com]
GitHub: [https://github.com/mohamedsade43]