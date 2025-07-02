# DocNow - Doctor Appointment Booking Platform

**DocNow** is a full-stack web application built to simplify and streamline the process of booking doctor appointments. It provides a responsive and user-friendly interface for Patients, Doctors, and Admins, and supports secure online payments. This project was developed as part of an individual software development project using the **MERN stack** (MongoDB, Express.js, React.js, Node.js).

## 🛠️ Tech Stack

- **Frontend**: React.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Authentication**: JSON Web Token (JWT)  
- **Payment Gateways**: Stripe, Razorpay  

---

## 🔑 Key Features

### 👤 Patient Features
- Register, log in, and manage appointments.
- Book, cancel, or reschedule appointments.
- Pay via **Cash**, **Stripe**, or **Razorpay**.
- Edit profile (name, email, address, gender, birthday, profile picture).

### 🩺 Doctor Features
- Log in to view and manage appointments.
- Track earnings and appointment statistics.
- Update profile details and availability.

### 🔧 Admin Features
- Add and manage doctor profiles.
- View analytics (total patients, doctors, appointments).
- Cancel or mark appointments as completed.

---

## 🏠 Pages Overview

### Home Page
- Search doctors by specialty.
- View featured doctors and informative sections.

### All Doctors
- Browse and filter doctors by specialty.
- Navigate to detailed doctor profile and booking form.

### Appointment Page
- Choose date, time, and payment method.
- Requires login to complete booking.

### User Profile
- View and edit personal details.
- Track past and upcoming appointments.

### Admin Panel
- Dashboard overview of system stats.
- Add/edit/delete doctors.
- Manage appointments system-wide.

---

## 💳 Payment Integration

- **Cash**
- **Stripe** (Card payments)
- **Razorpay** (UPI, card, net banking)

All payment processes are secure and encrypted.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/TharunKalugalla/DocNow.git
cd DocNow
