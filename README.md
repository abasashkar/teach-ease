# 📌 Attendance Management System

This project consists of:

•⁠  ⁠🔐 Auth Service (Backend)  
•⁠  ⁠📊 Attendance Service (Backend)  
•⁠  ⁠📱 Flutter Mobile App  
•⁠  ⁠🐳 Dockerized Setup  

---

# 🚀 Section 1: How To Run The Project

## ✅ Step 1: Clone Backend Repositories

Clone both backend services:

⁠ bash
git clone https://github.com/abasashkar/be-authservices
git clone https://github.com/abasashkar/be-attendanceservices
 ⁠

After cloning:

•⁠  ⁠Add your ⁠ .env ⁠ file inside both directories:
  - ⁠ be-authservices/ ⁠
  - ⁠ be-attendanceservices/ ⁠

Make sure environment variables are properly configured before running Docker.

---

## ✅ Step 2: Run Docker Compose

From the root directory (where your ⁠ docker-compose.yml ⁠ file exists), run:

⁠ bash
docker compose up --build
 ⁠

This will:

•⁠  ⁠Build all services  
•⁠  ⁠Start Auth Service  
•⁠  ⁠Start Attendance Service  
•⁠  ⁠Start PostgreSQL  
•⁠  ⁠Start Redis  

---

## ✅ Step 3: Clone Flutter Mobile App

⁠ bash
git clone https://github.com/abasashkar/attendance_app
 ⁠

Navigate into the Flutter project:

⁠ bash
cd attendance_app
 ⁠

---

## ✅ Step 4: Run Flutter App

⁠ bash
flutter pub get
flutter run
 ⁠

Make sure:

•⁠  ⁠Emulator is running *or*  
•⁠  ⁠Physical device is connected  

---

# 🎥 Section 2: Demo Video


<https://drive.google.com/file/d/1FAelX1G4lfyynZcMwVjzem0SCUbjru8a/view?usp=sharing>




## 📱 App Screenshots

<table align="center">
  <tr>
    <td><img src="https://github.com/user-attachments/assets/de224856-5fe0-4566-b3b0-d0f6f66575f6" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/62a2cbd0-66f8-40f8-98e7-ab098b93edd0" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/0b1b7c3e-50e5-47ec-b774-48d812129f32" width="250"/></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/869a6ae5-865a-4381-a75b-545f6790b70c" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/b98dc7fd-f20a-4450-aaec-226592edba66" width="250"/></td>
    <td><img src="https://github.com/user-attachments/assets/bf1c5966-5c2d-4e62-a6d7-44fe1c2da55e" width="250"/></td>
  </tr>
</table>



---

# 🛠 Tech Stack

•⁠  ⁠Node.js  
•⁠  ⁠Express.js  
•⁠  ⁠PostgreSQL  
•⁠  ⁠Redis  
•⁠  ⁠Prisma  
•⁠  ⁠Docker  
•⁠  ⁠Flutter  

---

# 📦 Architecture Overview

•⁠  ⁠*Auth Service* → Handles authentication & JWT  
•⁠  ⁠*Attendance Service* → Manages classes & attendance  
•⁠  ⁠*PostgreSQL* → Database  
•⁠  ⁠*Redis* → Caching  
•⁠  ⁠*Flutter* → Mobile client  

---

# 👨‍💻 Author

Abas Ashkar  
GitHub: [https://github.com/abasashkar](https://github.com/abasashkar)

---
