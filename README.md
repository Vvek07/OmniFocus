# OmniFocus 🎥

OmniFocus is a full-stack video collaboration platform inspired by Zoom, built with the MERN stack. The project aims to make virtual communication more seamless, secure, and developer-friendly. It's perfect for teams, classrooms, and online communities that rely on real-time video conferencing, chat, and screen sharing.

---

## 🔍 About The Project

While building this, I wanted to explore the world of real-time communication, peer-to-peer connection handling, and scalability. This app lets users create and join video meetings, chat live, and collaborate with ease. The interface is designed to be clean, responsive, and intuitive.

This was a solo project I built to level up my MERN stack skills, integrate WebRTC and Socket.IO, and understand how platforms like Zoom work under the hood.

---

## 🚀 Features

- ✅ One-click room creation & joining
- 🎥 Real-time video & audio calling (WebRTC)
- 💬 Real-time chat during meetings (Socket.IO)
- 🖥️ Screen sharing support
- 🧑‍🤝‍🧑 Participant list & controls
- 🔐 Unique room IDs for private meetings
- 📱 Responsive UI for all devices

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- WebRTC
- Socket.IO-client

**Backend:**
- Node.js
- Express.js
- Socket.IO
- MongoDB (optional for user/auth data)

---

## 📁 Folder Structure

```bash
OmniFocus/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
├── backend/
│   ├── server.js
│   ├── routes/
│   └── socket/
├── README.md
└── package.json

