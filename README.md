# 🚗 DriveEase - Car Rental Management System

A full-stack **Car Rental Management System** built using **Django**, featuring user authentication, car booking, admin management, and dynamic price calculation. This project is suitable for academic submissions, portfolio showcasing, and real-world learning.

---

## 📌 Features

### 👤 Authentication
- User Registration
- User Login & Logout
- Session-based authentication
- Protected routes using `@login_required`

### 🚘 Car Management
- Add, update, and delete cars via Admin Panel
- Set car availability
- Price per day configuration

### 📅 Booking System
- Book cars by selecting start and end dates
- Automatic total price calculation
- User-specific bookings
- Secure backend validation

### 🛠 Admin Panel
- Manage users
- Manage cars
- View all bookings

---

## 🧰 Tech Stack

| Layer        | Technology |
|--------------|------------|
| Backend      | Django (Python) |
| Frontend     | HTML, CSS |
| Database     | SQLite |
| Auth         | Django Auth |
| ORM          | Django ORM |

---

## 📁 Project Structure

Car_Rental/
├── bicycle/ # Main Django app
│ ├── models.py # Car & Booking models
│ ├── views.py # Auth & booking logic
│ ├── admin.py # Admin registrations
│ ├── urls.py
│ └── migrations/
│
├── templates/ # HTML templates
│ ├── index.html
│ ├── login.html
│ ├── register.html
│ └── booking.html
│
├── static/ # Static files (CSS, JS)
├── db.sqlite3 # Database
├── manage.py
└── settings.py

---

## 📸 Screenshot
