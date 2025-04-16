# 🕋 نَوى | NAWA – Smart Pilgrim Management System 🇸🇦

[![License: Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)

> A scalable, AI-powered, biometric-driven framework for managing Hajj & Umrah pilgrims in the Kingdom of Saudi Arabia.

---

## 📌 Overview

**"NAWA"** is a national-level initiative that reimagines the pilgrimage experience through a seamless integration of facial recognition, Edge AI computing, IoT beacons, and real-time behavioral analysis — from visa issuance to departure.

It ensures intelligent, contactless, and secure guidance for every pilgrim, with or without a smartphone.

---

## 🎯 Core Features

- **🎦 Biometric Verification**  
  Integration with **AWS Rekognition** and passport photos to detect illegal visa misuse (e.g. Umrah visas during Hajj).

- **📡 Offline Edge AI Processing**  
  **Jetson Nano** devices analyze live crowd density and behaviors — even with no internet.

- **📍 BLE-Based Guidance (for Non-Tech Users)**  
  **Estimote Beacons** + audio/visual stations to guide elderly or non-digital pilgrims.

- **📱 Flutter-Based Pilgrim App**  
  Real-time religious and logistical notifications in multiple languages.

- **🧠 Behavior Prediction**  
  AI models detect abnormal movements, overcrowding, or ritual violations in real-time.

---

## 🧩 Technical Stack

| Layer       | Technology                                       |
|-------------|--------------------------------------------------|
| Frontend    | Flutter (iOS + Android)                          |
| Backend     | FastAPI + Node.js + Webhooks                     |
| Database    | PostgreSQL + Firebase Realtime DB                |
| AI Models   | Python (Scikit-Learn + TensorFlow Lite)          |
| Cameras     | Hikvision + OpenCV + AWS Rekognition             |
| Edge Units  | NVIDIA Jetson Nano                               |
| IoT Layer   | Estimote BLE Beacons + NFC Tags                  |
| Security    | OAuth2 + JWT + TLS 1.3                           |

---

## 🗺️ System Flow

1. Visa issued → pilgrim facial data enrolled into Rekognition DB.
2. Arrival → NFC tag or facial recognition activates tracking.
3. Movement monitored via cameras + beacons + pilgrim app.
4. Real-time alerts sent to authorities if misuse, overstays, or crowding occurs.
5. Feedback collected via app & admin dashboard post-departure.

---

## 🔐 Compliance & Privacy

- ✅ End-to-End encrypted (AES-256 + TLS 1.3)
- ✅ No sensitive data stored on devices
- ✅ All biometric operations comply with **Saudi SDAIA policies**

---

## 🎯 Strategic Alignment with Hajj Vision 2030

NAWA directly addresses the strategic pillars of Saudi Arabia's Vision 2030 for pilgrimage innovation:

1. **Integrated Journey Management**  
   From visa issuance to real-time crowd control — one seamless digital thread.

2. **Spiritual and Service Enrichment**  
   Contextual alerts, multilingual guidance, and tailored nudges enhance the pilgrim's emotional and religious experience.

3. **Global Leadership in Crowd Management**  
   Uses edge analytics and predictive AI for real-time intervention and anomaly detection.

4. **Digital Transformation of Pilgrimage Services**  
   Combines IoT, biometric processing, and behavioral intelligence under one decentralized cloud-edge architecture.

5. **Sustainable Operations in Holy Sites**  
   Reuses existing infrastructure, leverages BLE beacons, and minimizes data transfer load with local inference.

6. **Fraud Prevention and Visa Misuse Detection**  
   Detects unauthorized entries (e.g., Umrah visas used during Hajj) using AWS Rekognition + immigration database API sync.

---

## 📄 Documentation & Licensing

- 📥 [Download the full NAWA System Proposal (PDF, Arabic)](https://github.com/Kapp1/nawa-smart-hajj/blob/main/docs/مشروع_نوى.pdf)
- ⚖️ Licensed under the [Apache License 2.0](LICENSE)  
  > *Commercial usage requires attribution and prior written permission.*

---

## 🇸🇦 Made in Saudi Arabia by [@Kapp1](https://github.com/Kapp1)

> **"نَوى يحوّل النية إلى بيانات، والبيانات إلى سلامة."**
