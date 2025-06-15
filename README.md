
# 🎵 Streamify — Fullstack Chat & Video Calling App

Streamify is a real-time chat and video calling web application designed for seamless communication. It includes messaging, group calls with screen sharing, JWT-based auth, and 32 unique UI themes, making it perfect for language exchange or social interaction.

> 🔗 Powered by Stream, Zustand, and TanStack Query.

---

## 🔗 Demo

- 🌍 [Live App](https://streamify-1zes.onrender.com)


---

## ✨ Features

- 💬 Real-time Messaging with Reactions & Typing Indicators
- 📹 1-on-1 & Group Video Calls with Screen Sharing
- 🔐 JWT Auth & Route Protection
- 🎨 32 UI Themes for Language Exchange
- ⚡ Zustand + TanStack Query State Management
- 📡 Stream API for Real-Time Backend
- 🚨 Frontend + Backend Error Handling
- 🧪 Environment Setup

---

## 🗂️ Folder Structure

```
Streamify/
├── backend/         # Node.js + Express + MongoDB
│   └── .env         # Backend env vars
├── frontend/        # React + Vite + Zustand
│   └── .env         # Frontend env vars
```

---

## ⚙️ Environment Variables

### Backend (`/backend/.env`)
```env
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

### Frontend (`/frontend/.env`)
```env
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## 🚀 Getting Started

### Backend
```bash
cd backend
npm install
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173)

---

## 🧰 Tech Stack

- **Frontend:** React, TailwindCSS, Zustand, TanStack Query, Vite
- **Backend:** Node.js, Express.js, MongoDB, JWT
- **Realtime:** Stream API
- **Deployment:**  Render

---

## ⭐️ Support

If you liked this project, give it a ⭐ on GitHub and share it!
