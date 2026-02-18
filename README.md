````markdown
# 📌 Attendance Management System

This project consists of:

- 🔐 Auth Service (Backend)
- 📊 Attendance Service (Backend)
- 📱 Flutter Mobile App
- 🐳 Dockerized Setup

---

# 🚀 Section 1: How To Run The Project

## ✅ Step 1: Clone Backend Repositories

Clone both backend services:

```bash
git clone https://github.com/abasashkar/be-authservices
git clone https://github.com/abasashkar/be-attendanceservices
```

After cloning:

- Add your `.env` file inside both:
  - `be-authservices/`
  - `be-attendanceservices/`

Make sure environment variables are properly configured before running Docker.

---

## ✅ Step 2: Run Docker Compose

From the root directory (where your `docker-compose.yml` file exists), run:

```bash
docker compose up --build
```

This will:

- Build all services
- Start Auth Service
- Start Attendance Service
- Start PostgreSQL
- Start Redis

---

## ✅ Step 3: Clone Flutter Mobile App

```bash
git clone https://github.com/abasashkar/attendance_app
```

Navigate into the Flutter project:

```bash
cd attendance_app
```

---

## ✅ Step 4: Run Flutter App

```bash
flutter pub get
flutter run
```

Make sure:
- Emulator is running OR
- Physical device is connected

---

# 🎥 Section 2: Demo Video

Demo Video URL:

```
<PASTE_YOUR_DEMO_VIDEO_LINK_HERE>
```

---

# 🛠 Tech Stack

- Node.js
- Express.js
- PostgreSQL
- Redis
- Prisma
- Docker
- Flutter

---

# 📦 Architecture Overview

- Auth Service → Handles authentication & JWT
- Attendance Service → Manages classes & attendance
- PostgreSQL → Database
- Redis → Caching
- Flutter → Mobile client

---

# 👨‍💻 Author

Abas Ashkar  
GitHub: https://github.com/abasashkar

---
````
