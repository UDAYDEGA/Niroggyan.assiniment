# 🏥 Doctor Appointment Booking System

A **Full Stack Web Application** built with **ReactJS** and **Node.js/Express** that allows Patients to book appointments, Doctors to manage their schedules, and Admins to control users and view analytics. The system features **JWT-based authentication**, **role-based access**, **dark/light theme toggle**, and a sleek, responsive design. 🌐

---

## 📌 Project Overview

The **Doctor Appointment System** enables seamless scheduling and management of medical appointments through three different user roles:

- 👨‍⚕️ **Doctors** can manage appointments, update availability, and view patient feedback.
- 🧑‍💼 **Patients** can register, log in, search doctors by specialization, book appointments, and view history.
- 🛠️ **Admins** can monitor platform activity, manage doctor/patient profiles, and access reports.

---

## 🛠️ Tech Stack

### 💻 Frontend (React.js)

- React Router v6 (Client-side routing)
- Context API (Theme toggle & auth context)
- JWT Token Auth & Protected Routes
- Dynamic Search & Filtering
- Responsive CSS (No Styled-Components)

### 🔧 Backend (Node.js + Express)

- JWT-based Role Authentication
- SQLite or MongoDB (pluggable DB support)
- REST APIs for login, register, doctor list, appointment CRUD
- Cookie-based session handling

---

## 🧑‍💼 User Roles

| Role   | Access                                                                 |
|--------|------------------------------------------------------------------------|
| Admin  | Manage all users, doctors, view system data, analytics dashboard       |
| Doctor | View booked slots, manage availability, patient info, feedback         |
| Patient| Search doctors, book appointments, view booking history                |

---

## 🔒 Authentication & Authorization

- 🔐 **JWT-based token validation**
- 🔐 **Role-based route protection**
- ✅ Persistent login using cookies
- ✅ Secure password storage (bcrypt)
- ⛔ Unauthorized access = redirect to login

---

## 📂 Folder Structure

```
doctor-appointment-app/
├── client/ (React App)
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── utils/
│   └── App.js
│
├── server/ (Express API)
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
```

---

## 🚀 Features

- 🌈 Dark/Light theme toggle with logo switch
- 🗂️ Doctor list with filters by specialization, rating
- 🔎 Search bar to find doctors quickly
- 🧾 Booking confirmation and appointment history
- 📜 Login/Register with real-time validations
- 📬 Contact doctor directly via provided mail/phone
- 🎯 Protected Dashboard views per user role

---

## 📌 How to Run the App

### 📁 Backend Setup

```bash
cd server
npm install
npm run dev
```

> Server runs on `http://localhost:5000`

### 💻 Frontend Setup

```bash
cd client
npm install
npm start
```

> React app runs on `http://localhost:3000`

---

## 🧪 API Endpoints

### Auth
- `POST /api/auth/login`
- `POST /api/auth/register`

### Doctor
- `GET /api/doctors/`
- `GET /api/doctors/:id`

### Appointment
- `POST /api/appointments/`
- `GET /api/appointments/history`
- `DELETE /api/appointments/:id`

---

## 🧠 Future Enhancements

- 🔔 Email/SMS notification on booking
- 📅 Calendar view for doctors
- 🧾 PDF receipt download for appointments
- 📈 Admin dashboard with charts
- 💬 Live chat between patient & doctor

---

## 👨‍💻 Developer Info

- 🔗 [GitHub](https://github.com/UDAYDEGA)
- 📧 udaydega10@gmail.com
- 📞 88974 27828
- 🌐 [LinkedIn](https://www.linkedin.com/in/uday-dega-44a31629a/)

---

## 🖼️ Screenshots

> Add screenshots of Login Page, Doctor List, Appointment Form, Admin Dashboard

---

## 📄 License

This project is licensed under the **MIT License**.

---

**🧠 Built with passion by a Full Stack Developer for a smoother healthcare experience.**
