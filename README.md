# 🎓 Automated Attendance System

An intelligent, secure, and efficient web-based attendance management system designed for educational institutions. The system automates attendance using **QR Code Generation**, **Face Verification**, and **Location Validation**, eliminating proxy attendance while reducing manual work for faculty.

---

## 📖 Overview

Traditional attendance systems are time-consuming and prone to proxy attendance. This project provides a smart solution that enables faculty to create attendance sessions and students to mark attendance only after passing multiple verification checks.

The system ensures that students are:

* Present in the correct classroom.
* Verified through facial recognition.
* Attending during the active session.

---

## ✨ Features

### 👨‍🏫 Faculty Module

* Secure Faculty Login
* Generate attendance sessions
* Create QR Codes for each class
* Select:

  * Department
  * Year
  * Semester
  * Subject
  * Period
  * Classroom
* View attendance records
* Monitor student attendance

### 👨‍🎓 Student Module

* Student Registration
* Secure Login
* Face Registration
* Scan QR Code
* Automatic attendance marking
* View attendance history

### 🔒 Security Features

* QR Code-based attendance
* Face Verification
* Location Validation
* Session-based attendance
* Duplicate attendance prevention

---

## 🛠️ Tech Stack

### Frontend

* React
* TypeScript
* Vite
* Tailwind CSS
* Axios

### Backend

* Node.js
* Express.js

### Database

* JSON (Current)
* MongoDB (Future Migration)

### Authentication

* JWT Authentication

---

## 📂 Project Structure

```
Automated-Attendance-System/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── data/
│   ├── users.json
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/sai1432-ss/Automated-Attendance-System.git
```

### 2. Move into Project

```bash
cd Automated-Attendance-System
```

---

## 🚀 Backend Setup

```bash
cd backend
npm install
npm start
```

Server runs on:

```
http://localhost:5000
```

---

## 🚀 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Application runs on:

```
http://localhost:5173
```

---

## 📸 System Workflow

1. Faculty logs in.
2. Faculty creates an attendance session.
3. QR Code is generated.
4. Students scan the QR Code.
5. System verifies:

   * Face
   * Location
   * Session validity
6. Attendance is recorded.
7. Faculty can view attendance reports.

---

## 📋 Future Enhancements

* MongoDB Database
* Face Recognition using AI
* Geofencing
* Attendance Analytics Dashboard
* Email Notifications
* Mobile Application
* Admin Dashboard
* Cloud Deployment

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📜 License

This project is intended for educational purposes.

---

## 👨‍💻 Author

**Sai Satish**

GitHub: https://github.com/sai1432-ss

---

## ⭐ Support

If you found this project helpful, don't forget to **Star ⭐ the repository**.
