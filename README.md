# 🌍 Realtime Tracking App

[![Node.js](https://img.shields.io/badge/Node.js-v18.0-green)](https://nodejs.org/) 
[![Express](https://img.shields.io/badge/Express-5.1.0-blue)](https://expressjs.com/) 
[![Socket.IO](https://img.shields.io/badge/Socket.IO-4.8.1-orange)](https://socket.io/) 
[![Leaflet](https://img.shields.io/badge/Leaflet-1.9.4-brightgreen)](https://leafletjs.com/) 
[![License](https://img.shields.io/badge/License-MIT-red)](LICENSE)

A **Realtime Location Tracking Web Application** built with **Node.js**, **Express**, **Socket.IO**, and **Leaflet.js**. Track multiple users live on a map with interactive markers and automatic updates.

---

## 🎥 Demo

<img width="1919" height="998" alt="Realtime Tracking App Demo" src="https://github.com/user-attachments/assets/03da8576-c491-4232-aae4-18ff2f53e16b" />

---

## ⚡ Features

- 🌐 **Real-time location tracking** for multiple users
- 🗺️ **Interactive map** using **Leaflet.js** and **OpenStreetMap** tiles
- 👤 **Automatic marker management** - markers added/removed as users connect/disconnect
- 📍 **High-accuracy location** updates using browser's `navigator.geolocation`
- 🖥️ **Fully responsive** and lightweight front-end design

---

## 🛠️ Technologies Used

- **Node.js** – Backend runtime environment
- **Express.js** – Web server framework
- **Socket.IO** – Real-time bi-directional communication
- **EJS** – Templating engine for views
- **Leaflet.js** – Interactive maps library
- **OpenStreetMap** – Free map tiles provider

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/realtime-tracker.git
cd realtime-tracker
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the Application
```bash
node app.js
```

### 4. Access the Application
Open your browser and navigate to:
```
http://localhost:3000
```

---

## 🖥️ Usage

1. **Open the application** on multiple devices or browser tabs
2. **Allow location access** when prompted by your browser
3. **View real-time tracking** - your location marker will appear on the map
4. **Monitor multiple users** - see all connected users updating live
5. **Automatic cleanup** - user markers are removed when they disconnect

---

## 📂 Project Structure

```
realtime-tracker/
│
├── public/
│   ├── css/
│   │   └── style.css          # Frontend styles
│   └── js/
│       └── script.js          # Client-side JavaScript
│
├── views/
│   └── index.ejs              # Main application view
│
├── app.js                     # Main server file
├── package.json               # Project dependencies
└── README.md                  # Project documentation
```

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## 🙏 Acknowledgements

- **Leaflet.js** – Open-source interactive maps library
- **OpenStreetMap** – Free and open geographic data
- **Socket.IO** – Real-time communication framework
- Inspired by real-time location tracking applications

---

## 🚀 Future Enhancements

- 🔐 User authentication system
- 👥 Group tracking with user labels/names
- 📊 Location history and analytics
- 📱 Mobile-optimized UI with push notifications
- 🔔 Custom alerts and geofencing capabilities

---

**Happy Tracking! 🌐🚀**
