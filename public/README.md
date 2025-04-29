# 🌐 Unity Serve – An Integrated Platform for Empowering NGO’s in India

Unity Serve is a humanitarian web platform built to connect donors with NGOs and individuals in need. The platform supports donations of **blood, books, clothes, food**, and more. With Firebase as the backend, it ensures secure authentication, real-time data handling, and reliable hosting — all centered around making social good easy and accessible.

## 🚀 Live Demo

🔗 [unityservengo-demo.web.app](https://unityservengo-demo.web.app)

---

## 🧠 Project Overview

Unity Serve simplifies and streamlines the donation process through:

- 📝 **Donation forms** for various needs (blood, books, clothes, food)
- 🔐 **Firebase Authentication** for secured admin login
- 🔍 **Admin Dashboard** to view and act upon submitted donor applications
- 📡 **Firebase Hosting** for global reach
- 💸 **GPay Integration** via direct link for donations
- 🤖 **BotPress Chatbot** for multilingual donor guidance

---

## 🛠️ Tech Stack

| Technology            | Purpose                                           |
|------------------------|---------------------------------------------------|
| **Firebase**           | Authentication, Firestore Database, Hosting      |
| **Firestore Subcollections** | Store structured donation data per form     |
| **HTML/CSS/JavaScript**| Frontend Development                            |
| **BotPress**           | Multilingual Chatbot Assistance                  |
| **GPay UPI Link**      | Payment Processing via UPI                       |
| **GitHub**             | Version Control & Collaboration                  |

---

## ✨ Key Features

- 📄 **Donation Forms**  
  All forms capture user inputs and send them directly to **Firestore subcollections**, organized under specific categories.

- 🔐 **Firebase Authentication**  
  Admin access is protected by Firebase Auth, ensuring secure login before any data review.

- 🗃️ **Admin Panel (Dashboard)**  
  Connected to Firestore, this allows the admin to:
  - View form submissions
  - Accept/Reject donation applications
  - Act on entries directly from the dashboard

- 💳 **GPay Payment Link Integration**  
  Instead of a full payment gateway, a **GPay UPI link** is provided for users to make quick contributions.

- 🤖 **BotPress Chatbot**  
  Offers navigation and multilingual assistance to users and donors, helping them find what they need quickly.

- 🌐 **Firebase Hosting**  
  The entire project is hosted and served via Firebase Hosting. Configuration is defined in `firebase.json` and the `/firebase` directory.

---

## 🔐 Firebase Authentication

- Used to restrict access to the admin dashboard
- Admins can sign in securely and manage application data

---


