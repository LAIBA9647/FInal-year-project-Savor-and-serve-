# Savor and Serve – A Role-Based Donation Platform
"🚧 Project Status: In Progress"
## Overview

**Savor and Serve** is a full-stack, secure donation web application that connects **donors**, **registered NGOs**, and **grocery suppliers** to streamline the distribution of essential items to underprivileged communities. Built using the **MERN stack**, this platform integrates **Stripe Connect** for seamless payment handling and **Twilio** for real-time SMS notifications. The project emphasizes data privacy, role-based access, and secure operations using modern authentication and encryption techniques.

---

## Tech Stack

- **Frontend:** React.js, Material UI, HTML, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with encryption at rest)
- **Authentication & Security:** JWT, TLS/HTTPS, Role-Based Access Control (RBAC)
- **Payment Integration:** Stripe (Custom Accounts, Connected Accounts)
- **Communication:** Twilio SMS API
- **Deployment:** Vercel / Render / Railway (as applicable)

---

## Features

### 🔐 Secure Authentication
- JWT-based login and signup
- Role-based access: Donor, NGO, and Grocery Supplier
- Encrypted passwords and session handling

### 💳 Donation Management
- Donors can securely donate via Stripe
- NGOs and Grocery Suppliers manage received funds and requests
- Real-time status tracking of donations and grocery requests

### 📱 Real-Time Notifications
- Twilio SMS alerts for donation confirmations and impact updates

### 📊 Dashboards
- Each role has a custom dashboard:
  - **Donor Dashboard:** track donations, register impactees (beneficiaries), view donation history
  - **NGO Dashboard:** manage impact data, issue donation requests, verify beneficiaries
  - **Grocery Supplier Dashboard:** fulfill grocery requests, view order history

### 🔍 Transparency & Trust
- Impact meter showing the effect of donations
- Audit logging for sensitive actions

---

## Project Objectives

- Bridge the gap between donors and verified NGOs
- Ensure transparency and traceability of donations
- Facilitate scalable, secure, and fast operations in donation workflows
- Build a user-friendly platform for all stakeholders with a real-time communication system

---



## How to Run Locally

1. Clone the repository
2. Install dependencies in both frontend and backend directories
3. Add your environment variables:
   - Stripe API keys
   - Twilio credentials
   - MongoDB URI
   - JWT Secret
4. Run backend: `npm start`
5. Run frontend: `npm start`
6. Visit `http://localhost:3000`

---

## Credits

Developed by **Laiba Sakhawat**  
Bachelor of Science in Information Technology  
Air University, Islamabad  
2021 – 2025

---

## License

This project is for academic purposes. All rights reserved © Laiba Sakhawat 2025.
