# 🟠 Backend — Data and Communication Management

This section is responsible for building the server that manages incoming data from smart devices and serves both the Android application and the website through a unified and secure API.

---

## 🚀 Technologies Used

- **Laravel** — A modern PHP framework for building powerful and scalable servers.
- **Sanctum** — A simple and secure authentication system for mobile and web applications.
- **MySQL** — A flexible database for storing readings and information.
- **WebSocket (Optional)** — For live data streaming from the wearable device to applications.
- **REST API** — For creating standardized communication endpoints between the server and the applications.

---

## 🌐 Backend Objectives

- Receive sensor data (such as heart rate, motion, etc.) from the smart wearable device.
- Store the data in an organized and secure manner in the database.
- Provide API endpoints for the Android application and the website to access and display data.
- Support real-time notifications and alerts when values exceed predefined thresholds.
- Manage user accounts and handle authentication and authorization sessions.

---

## 📦 Project Structure

```bash
backend/
├── app/Http/Controllers/    # Logic for handling data and APIs
├── app/Models/               # ORM models linked to database tables
├── database/migrations/      # Files for creating and modifying database tables
├── routes/api.php            # API route definitions
├── config/                   # Project configuration files
├── public/                   # Public entry points (if needed)
└── composer.json             # Project dependencies
