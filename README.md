# 🌍 Realtime Tracking App

[![Node.js](https://img.shields.io/badge/Node.js-v18.0-green)](https://nodejs.org/) 
[![Express](https://img.shields.io/badge/Express-5.1.0-blue)](https://expressjs.com/) 
[![Socket.IO](https://img.shields.io/badge/Socket.IO-4.8.1-orange)](https://socket.io/) 
[![Leaflet](https://img.shields.io/badge/Leaflet-1.9.4-brightgreen)](https://leafletjs.com/) 
[![License](https://img.shields.io/badge/License-MIT-red)](LICENSE)

A **Realtime Location Tracking Web Application** built with **Node.js**, **Express**, **Socket.IO**, and **Leaflet.js**. Track multiple users live on a map with interactive markers and automatic updates.

---

## 🎥 Demo

<img width="1919" height="998" alt="image" src="https://github.com/user-attachments/assets/03da8576-c491-4232-aae4-18ff2f53e16b" />


---

## ⚡ Features
- 🌐 Real-time location tracking for multiple users.  
- 🗺️ Interactive map using **Leaflet.js** and **OpenStreetMap** tiles.  
- 👤 Automatic marker addition/removal as users connect/disconnect.  
- 📍 High-accuracy location updates using the browser's `navigator.geolocation`.  
- 🖥️ Fully responsive and lightweight front-end.

---

## 🛠️ Technologies Used
- **Node.js** – Backend runtime environment  
- **Express.js** – Web server framework  
- **Socket.IO** – Real-time bi-directional communication  
- **EJS** – Templating engine  
- **Leaflet.js** – Interactive maps  
- **OpenStreetMap** – Free map tiles  

---

## ⚙️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/realtime-tracker.git
cd realtime-tracker
Install dependencies

bash
Copy code
npm install
Run the application

bash
Copy code
node app.js
Open your browser and visit:

arduino
Copy code
http://localhost:3000
🖥️ Usage
Open the app on multiple devices or browser tabs.

Allow location access when prompted.

Your location marker will appear on the map and update in real-time.

Disconnecting users will have their markers automatically removed.

📂 Project Structure
pgsql
Copy code
realtime-tracker/
│
├── public/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
├── views/
│   └── index.ejs
│
├── app.js
├── package.json
└── README.md
📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.

🙏 Acknowledgements
Leaflet.js – Open-source interactive maps.

OpenStreetMap – Free map tiles.

Socket.IO – Real-time communication.

Inspired by real-time location tracking applications.

🚀 Next Steps / Improvements
Add user authentication.

Group tracking with labels or names.

History of locations.

Mobile-friendly UI with push notifications.

Happy Tracking! 🌐🚀
