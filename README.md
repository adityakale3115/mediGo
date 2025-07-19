# 🚑 MediGo – Emergency Medical Assistance Platform

MediGo is a real-time emergency response platform that connects users in medical distress with the nearest available ambulance drivers.

---

## 🔧 Features

### 👤 User App
- Login/Sign up using Firebase Authentication
- Send emergency request with live geolocation
- View real-time status updates (`pending` or `accepted`)
- See assigned ambulance driver details
- Safety tips during emergencies

### 🚑 Ambulance App
- Realtime dashboard of emergency requests
- Accept or decline incoming requests
- Track status (`pending`, `accepted`)
- Mark request as completed (removes from system)
- Toggle availability status

---

## 🛠 Tech Stack

| Frontend     | Backend / Services |
|--------------|--------------------|
| React        | Firebase Auth      |
| React Router | Firebase Firestore |
| CSS Modules  | Geolocation API    |


---

## 🚀 Getting Started

### 1. Clone the Repo

    ```bash
    git clone https://github.com/adityakale3115/mediGo.git
    cd mediGo
    npm install

## 📸 Screenshots

### 👤 User Dashboard
![User Dashboard](./screenshots/a.png)

### 🚑 Ambulance Dashboard
![Ambulance Dashboard](./screenshots/b.png)
