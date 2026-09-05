<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2&height=200&section=header&text=Uber%20Clone&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Uber Clone Banner" width="100%" />

  <p align="center">
    <strong>A production-ready, full-stack MERN ride-hailing platform with real-time geolocation tracking, dynamic fare calculation, and role-based administrative control.</strong>
  </p>

  <p align="center">
    <a href="https://github.com/ajayxuns/Uber-Clone-MERN-/stargazers"><img src="https://img.shields.io/github/stars/ajayxuns/Uber-Clone-MERN-?style=for-the-badge&color=FFE600&logo=star&logoColor=black" alt="Stars" /></a>
    <a href="https://github.com/ajayxuns/Uber-Clone-MERN-/network/members"><img src="https://img.shields.io/github/forks/ajayxuns/Uber-Clone-MERN-?style=for-the-badge&color=007AFF&logo=git&logoColor=white" alt="Forks" /></a>
    <a href="https://github.com/ajayxuns/Uber-Clone-MERN-/issues"><img src="https://img.shields.io/github/issues/ajayxuns/Uber-Clone-MERN-?style=for-the-badge&color=FF3B30&logo=github" alt="Issues" /></a>
    <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-34C759?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License" /></a>
  </p>

  <h3>
    <a href="#-quick-start">Quick Start</a> •
    <a href="#-features">Features</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-architecture">Architecture</a> •
    <a href="#-contributing">Contributing</a>
  </h3>

</div>

---

## ⚡ Overview

This project is a high-performance clone of the **Uber** web platform built entirely on the **MERN** stack. Designed with precision, it mirrors core urban mobility workflows: pinpointing locations via geospatial APIs, selecting dynamic vehicle tiers, calculating route distances on the fly, and tracking rides end-to-end.

---

## 🚀 Key Features

<table>
  <tr>
    <td width="50%">
      <h4>🔐 Identity & Security</h4>
      <ul>
        <li>Stateless authentication via <code>JSON Web Tokens (JWT)</code></li>
        <li>Secure password hashing using <code>bcryptjs</code></li>
        <li>Role-based access control (Passengers, Drivers, Admins)</li>
      </ul>
    </td>
    <td width="50%">
      <h4>🗺️ Real-Time Navigation</h4>
      <ul>
        <li>Interactive maps powered by <b>Mapbox / Google Maps API</b></li>
        <li>Predictive address autocomplete and route polyline generation</li>
        <li>Live pickup and drop-off coordinate tracking</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h4>💰 Dynamic Pricing Engine</h4>
      <ul>
        <li>Real-time distance and estimated duration computation</li>
        <li>Tiered rate matrix (UberX, Comfort, Black)</li>
        <li>Automated bill splitting and receipt generation</li>
      </ul>
    </td>
    <td width="50%">
      <h4>🛠️ Unified Control Center</h4>
      <ul>
        <li>Comprehensive Admin telemetry for active trips</li>
        <li>Fleet and passenger profile management</li>
        <li>Dynamic price surge overrides and operational analytics</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![MUI](https://img.shields.io/badge/Material--UI-007FFF?style=flat-square&logo=mui&logoColor=white) ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white) |
| **Database** | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white) |
| **Services & Auth** | ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Mapbox](https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white) ![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white) |

</div>

---

## 🏁 Quick Start

### Prerequisites
* Node.js `>= 18.x`
* npm `>= 9.x`
* MongoDB Atlas cluster or local MongoDB instance running on `localhost:27017`
* Mapbox or Google Cloud Platform API key

### 1. Clone the Repository
```
git clone https://github.com/ajayxuns/Uber-Clone-MERN-.git
cd Uber-Clone-MERN-
```

### 2. Environment Configuration
Create a .env file in the server directory and populate the variables:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_token
MAPS_API_KEY=your_mapbox_or_google_maps_key
```

### 3. Install & Launch
```
cd server
npm install
npm start
```
```
cd client
npm install
npm start
```

### 📂 Project Architecture
```
Uber-Clone-MERN-/
├── client/                 # React frontend application
│   ├── public/             # Static assets & index.html
│   └── src/
│       ├── components/     # UI building blocks (Map, Navbar, Cards)
│       ├── pages/          # Primary application views (Home, Ride, Admin)
│       ├── services/       # Axios API client handlers
│       └── context/        # Authentication & State management
├── server/                 # Express backend API
│   ├── config/             # DB connection & external service configs
│   ├── controllers/        # Request processing & business logic
│   ├── models/             # Mongoose schemas (User, Ride, Location)
│   ├── routes/             # REST endpoints (authRoutes, rideRoutes)
│   └── middleware/         # Token validation & access handlers
└── README.md
```

## 📜 License
Distributed under the MIT License. See LICENSE for more information.

## 📬 Contact & Support
Ajay Bankar — @ajayxuns


