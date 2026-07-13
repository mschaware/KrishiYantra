# 🌾 KrishiYantra

An AI-powered Smart Agriculture Platform that helps farmers make data-driven decisions using Artificial Intelligence, IoT, and Real-Time Analytics.

## 📌 Overview

KrishiYantra is a full-stack smart farming solution designed to improve agricultural productivity, optimize resource utilization, and increase farmers' profitability.

The platform combines AI, IoT, and cloud technologies to provide:

- 🌱 AI-powered Crop Recommendation
- 💧 Smart Irrigation using IoT Sensors
- 📈 Market Price Forecasting
- 🛒 Farmer Marketplace
- 📍 Smart Logistics & Geo-location
- 📊 Real-time Farm Monitoring

---

## 🚀 Live Demo

🔗 https://krishi-yantra-mayur-chawares-projects.vercel.app/

---

## 🎯 Problem Statement

Many farmers still rely on traditional farming methods, making it difficult to:

- Choose the right crop
- Monitor soil conditions
- Predict future market prices
- Connect directly with buyers
- Reduce water consumption

KrishiYantra addresses these challenges through an intelligent digital farming ecosystem.

---

# ✨ Features

### 🌱 AI Crop Recommendation

Recommends suitable crops based on:

- Soil Nutrients (NPK)
- pH Value
- Weather Conditions
- Historical Data

---

### 💧 Smart Irrigation

Uses IoT sensors to monitor:

- Soil Moisture
- Temperature
- Humidity

Automatically notifies farmers when irrigation is required.

---

### 📈 Price Prediction

Predicts future crop prices using:

- Historical Market Data
- Seasonal Trends
- AI Models

Helping farmers sell at the right time.

---

### 🛒 Marketplace

Allows farmers to:

- Connect directly with buyers
- Lease farming equipment
- Discover nearby markets

---

### 📊 Real-Time Dashboard

Displays:

- Live sensor data
- Crop insights
- AI recommendations
- Farm analytics

---

# 🏗️ System Architecture

```
                    IoT Sensors
                         │
                         ▼
                  Microcontroller
                         │
                         ▼
                  Flask REST APIs
                         │
      ┌──────────────────┼─────────────────┐
      ▼                  ▼                 ▼
 PostgreSQL          AI Engine         MongoDB
      │                  │
      └──────────┬───────┘
                 ▼
            React Frontend
                 │
                 ▼
              Farmers
```

---

# 🛠️ Tech Stack

## Frontend

- React.js
- JavaScript
- HTML5
- CSS3

## Backend

- Python
- Flask
- REST APIs

## Databases

- PostgreSQL
- MongoDB

## AI / ML

- LLaMA 7B
- ReAct AI Agent
- Machine Learning

## IoT

- ESP8266
- DHT11
- Soil Moisture Sensors

## Cloud

- Firebase
- AWS

## Notifications

- Twilio WhatsApp API

---

# 📂 Project Structure

```
KrishiYantra/

├── client/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── services/
│
├── server/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── utils/
│   └── app.py
│
├── ai/
│
├── iot/
│
├── database/
│
└── README.md
```

*(Update this section to match your actual folder structure.)*

---

# 🔄 Data Flow

```
IoT Sensors
      │
      ▼
ESP8266 Microcontroller
      │
HTTP Requests
      │
      ▼
Flask REST API
      │
      ▼
PostgreSQL Database
      │
      ▼
AI Recommendation Engine
      │
      ▼
React Dashboard
      │
      ▼
Farmer
```

---

# 💡 Engineering Decisions

During development, I focused on:

- Component-based React architecture
- Modular Flask APIs
- Separation of concerns
- Reusable UI components
- RESTful API design
- Scalable backend structure
- Clean folder organization
- Maintainable codebase

---

# 📷 Screenshots


<img width="1909" height="2728" alt="screencapture-krishi-yantra-mayur-chawares-projects-vercel-app-2026-07-13-22_29_15" src="https://github.com/user-attachments/assets/67633658-1ff8-46c9-9fd0-17843114b83d" />

<img width="1909" height="1004" alt="screencapture-krishi-yantra-mayur-chawares-projects-vercel-app-dashboard-2026-07-13-22_32_29" src="https://github.com/user-attachments/assets/feb8e713-95f9-4dc6-8ef6-7f359da07c00" />

<img width="1848" height="880" alt="image" src="https://github.com/user-attachments/assets/56ceadf5-b40f-481e-9268-fa6fd7ef1e3f" />

<img width="1909" height="1816" alt="screencapture-krishi-yantra-mayur-chawares-projects-vercel-app-market-2026-07-13-22_34_57" src="https://github.com/user-attachments/assets/0dbfdf3e-e36e-42d4-bdc3-f2a99355eeff" />

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/mschaware/KrishiYantra.git
```

## Navigate

```bash
cd KrishiYantra
```

## Frontend

```bash
npm install
npm run dev
```

## Backend

```bash
pip install -r requirements.txt
python app.py
```

---

# 🔮 Future Improvements

- Mobile Application
- Offline Support
- Drone Integration
- Satellite Image Analysis
- Multi-language Support
- Advanced AI Models
- Weather Prediction
- Precision Farming

---

# 👨‍💻 Author

**Mayur Chaware**

- LinkedIn: [https://linkedin.com/in/YOUR_LINKEDIN](https://www.linkedin.com/in/mayur-chaware/)
- GitHub: https://github.com/mschaware

---

# ⭐ Highlights

- AI + IoT Powered Agriculture Platform
- Full Stack Application
- Real-Time Monitoring
- REST API Architecture
- Cloud Ready
- Modular & Scalable Design

---

If you found this project interesting, consider giving it a ⭐ on GitHub.
