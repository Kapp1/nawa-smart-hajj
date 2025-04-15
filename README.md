# 🕋 نَوى | NAWA – Smart Pilgrim Management System 🇸🇦

> A scalable, AI-powered, biometric-driven framework for managing Hajj & Umrah pilgrims in the Kingdom of Saudi Arabia.

---

## 📌 Overview

**"NAWA"** is a national-level initiative that reimagines the pilgrimage experience through a seamless integration of facial recognition, edge AI computing, IoT beacons, and real-time behavioral analysis — from visa issuance to departure.

It ensures intelligent, contactless, and secure guidance for every pilgrim, with or without a smartphone.

---

## 🎯 Core Features

- **🎦 Biometric Verification**  
  Integration with AWS Rekognition and passport photos to detect illegal visa misuse (e.g. Umrah visas during Hajj).

- **📡 Offline Edge AI Processing**  
  Jetson Nano devices analyze live crowd density and behaviors, even with no internet.

- **📍 BLE-Based Guidance (for Non-Tech Users)**  
  Estimote Beacons + audio/visual nodes auto-guide elderly/non-digital pilgrims.

- **📱 Flutter-Based Pilgrim App**  
  Real-time religious and logistical notifications in multiple languages.

- **🧠 Behavior Prediction**  
  AI models detect abnormal movements, overcrowding, or schedule violations in real-time.

---

## 🧩 Technical Stack

| Layer       | Technology                                       |
|-------------|--------------------------------------------------|
| Frontend    | Flutter (iOS + Android)                          |
| Backend     | FastAPI + Node.js + Webhooks                     |
| Database    | PostgreSQL + Firebase Realtime DB                |
| AI Models   | Python (Scikit-Learn + TensorFlow Lite)          |
| Cameras     | Hikvision Smart Cams + OpenCV + AWS Rekognition  |
| Edge Units  | NVIDIA Jetson Nano                               |
| IoT Layer   | Estimote BLE Beacons + NFC Tags                  |
| Security    | OAuth2 + JWT + TLS 1.3                           |

---

## 🗺️ System Flow

1. Visa issued → pilgrim facial data enrolled into Rekognition DB.
2. Arrival → NFC or facial recognition activates tracking.
3. Movement monitored via cameras + beacons + app.
4. Real-time notifications sent to authorities if misuse or overcrowding occurs.
5. Post-ritual feedback collected via app and control panel.

---

## 🔐 Compliance & Privacy

- End-to-End encrypted (AES-256 + TLS 1.3)
- No sensitive data stored on devices
- All biometric processing complies with Saudi regulations & SDAIA framework

---

## 📄 Supporting Documentation

📥 [Download the full NAWA System Proposal (Arabic PDF)](https://github.com/Kapp1/nawa-smart-hajj/blob/main/docs/%D9%85%D8%B4%D8%B1%D9%88%D8%B9%20%D9%86%D9%88%D9%89.pdf)


---

## 🇸🇦 Made in Saudi Arabia by [@Kapp1](https://github.com/Kapp1)

> Driven by faith. Designed by logic. Built for billions.
