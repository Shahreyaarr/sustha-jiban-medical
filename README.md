<p align="center">
  <img src="https://img.shields.io/badge/Sustha%20Jiban-Medical%20Centre-blue?style=for-the-badge&logo=heartbeat" alt="Sustha Jiban Medical Centre" />
</p>

<h1 align="center">🏥 Sustha Jiban Medical Centre</h1>

<p align="center">
  <b>সুস্থ জীবন মেডিকেল সেন্টার</b><br>
  <em>Advanced Healthcare Management System</em>
</p>

<p align="center">
  <a href="https://susthajiban.up.railway.app/">
    <img src="https://img.shields.io/badge/LIVE_DEMO-Click_Here-success?style=for-the-badge&logo=vercel" alt="Live Demo" />
  </a>
  <a href="https://digitaledgesolutions.cloud/">
    <img src="https://img.shields.io/badge/Developed_By-Digital_Edge_Solutions-purple?style=for-the-badge&logo=cloud" alt="Digital Edge Solutions" />
  </a>
</p>

---

## 🌟 Project Overview

**Sustha Jiban Medical Centre** is a comprehensive, full-stack healthcare management platform developed for a **Kolkata-based super speciality hospital**. The system streamlines patient appointments, doctor management, and administrative operations with a modern, bilingual (English/Bengali) interface.

> 🏆 **Live Application:** [https://susthajiban.up.railway.app/](https://susthajiban.up.railway.app/)

---

## ✨ Key Features

### 🩺 For Patients
| Feature | Description |
|---------|-------------|
| **Online Appointment Booking** | Real-time doctor availability with time slot selection |
| **Bilingual Support** | Seamless English ↔ Bengali language toggle |
| **Doctor Profiles** | Detailed specialist information with qualifications & timings |
| **Emergency Contact** | One-click emergency calling functionality |

### 👨‍⚕️ For Administrators
| Feature | Description |
|---------|-------------|
| **Secure Admin Dashboard** | JWT-authenticated admin panel |
| **Appointment Management** | Confirm, cancel, or reschedule appointments |
| **Patient Records** | Complete patient history and visit tracking |
| **Data Export** | CSV export for appointments and analytics |
| **Real-time Statistics** | Live dashboard with key metrics |

---

## 🛠️ Technology Stack

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=flat-square&logo=font-awesome&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=json-web-tokens&logoColor=white)

### Deployment
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

## 🏗️ System Architecture
┌─────────────────────────────────────────────────────────┐
│                    CLIENT LAYER                         │
│  ┌─────────────┐  ┌──────────────┐  ┌──────────────┐   │
│  │   Patient   │  │   Admin      │  │   Public     │   │
│  │   Portal    │  │   Dashboard  │  │   Website    │   │
│  └─────────────┘  └──────────────┘  └──────────────┘   │
└─────────────────────────────────────────────────────────┘
│
┌─────────────────────────────────────────────────────────┐
│                   API GATEWAY (Express)                 │
│  ┌─────────────┐  ┌──────────────┐  ┌──────────────┐   │
│  │  /api/      │  │  /api/admin  │  │   Static     │   │
│  │  doctors    │  │  login       │  │   Files      │   │
│  │  appointments│  │  stats       │  │              │   │
│  │  slots      │  │  export      │  │              │   │
│  └─────────────┘  └──────────────┘  └──────────────┘   │
└─────────────────────────────────────────────────────────┘
│
┌─────────────────────────────────────────────────────────┐
│                  DATA LAYER (MongoDB)                   │
│  ┌─────────────┐  ┌──────────────┐  ┌──────────────┐   │
│  │   Doctors   │  │ Appointments │  │   Patients   │   │
│  │   Collection│  │  Collection  │  │  Collection  │   │
│  └─────────────┘  └──────────────┘  └──────────────┘   │
└─────────────────────────────────────────────────────────┘
plain
Copy

--
