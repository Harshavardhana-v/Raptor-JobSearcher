# 🚀 JobHud – Smart Career Guidance & Job Recommendation App

JobHud is a full-stack career enhancement platform built using **Flutter** (frontend) and **Node.js + Express + MySQL** (backend).  
It helps users explore jobs, check culture fit, get daily tips, track saved jobs, stay updated with tech trends, and prepare for interviews — all in one application.

---

## 📸 App Screenshots
> Upload your app images later by replacing the file paths below.

| Screenshot | Description |
|-----------|-------------|
| ![img](assets/ss1.png) | Home Screen |
| ![img](assets/ss2.png) | Explore Jobs |
| ![img](assets/ss3.png) | Job Details |
| ![img](assets/ss4.png) | Profile Page |
| ![img](assets/ss5.png) | Daily Tips |
| ![img](assets/ss6.png) | Culture Quiz |
| ![img](assets/ss7.png) | Interview Prep |
| ![img](assets/ss8.png) | Saved Jobs |

---

## 🛠️ Tech Stack

### **Frontend (Flutter)**
- Flutter & Dart  
- Provider (State Management)  
- REST API Integration  
- Material UI & Navigation  
- Android, iOS, Web compatible  

### **Backend (Node.js + Express)**
- Express.js Routing  
- MySQL Database  
- JWT Authentication  
- Modular Architecture  
- Custom Services & Middleware  

---

## 📂 Folder Structure

### **Backend Structure (`backend/`)**
backend/
├── middleware/
├── node_modules/
├── routes/
│ ├── auth.js
│ ├── profile.js
│ └── tips.js
├── services/
│ └── authService.js
├── db.js
├── server.js
├── .env
├── package.json
└── README.md
### **Flutter App Structure (`jobhud/`)**
jobhud/
├── lib/
│ ├── models/
│ ├── providers/
│ ├── screens/
│ │ ├── auth/
│ │ ├── dashboard/
│ │ └── profile_screen.dart
│ ├── services/
│ └── main.dart
├── android/
├── ios/
├── web/
├── pubspec.yaml
└── README.md


## ⚙️ Setup Guide

# 1️⃣ Backend Setup (Node.js + Express + MySQL)

### **Install Dependencies**

cd backend
npm install
Create .env File
Copy code
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=jobhud
JWT_SECRET=your_jwt_secret
PORT=5000


Start Backend Server
npm start

Flutter Setup (Frontend)
Install Dependencies
cd jobhud
flutter pub get

Set Your Backend API URL

Inside api_service.dart:

final String baseUrl = "http://10.0.2.2:5000"; // Android Emulator
// or
final String baseUrl = "http://localhost:5000"; // Web

Run App
flutter run


Set Your Backend API URL

Inside api_service.dart:

final String baseUrl = "http://10.0.2.2:5000"; // Android Emulator
// or
final String baseUrl = "http://localhost:5000"; // Web

Run App
flutter run
