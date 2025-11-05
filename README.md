# 💬 Real-Time Chat Application

A real-time chat platform built with **Node.js**, **Express**, **Socket.io**, and **React**, featuring instant messaging, private chats, delivery acknowledgments, message pagination, search functionality, and responsive UI for both desktop and mobile users.

---

## 🧭 Project Overview

This project is a lightweight chat system that demonstrates modern web socket communication using **Socket.io**.  
Users can:
- Join different chat rooms
- Send and receive messages in real-time
- React to messages
- Receive delivery acknowledgments
- Search through chat history
- Reconnect automatically after disconnection  
All messages are stored **in memory** (for demo purposes) rather than in a database.

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone
cd realtime-chat-app

### 2. Install server dependencies
cd server
npm install

### 3. Install client dependencies
cd client
npm install

### 4. Start the backend server
cd server
npm run dev
By default, the server runs on http://localhost:5000

### 5. Start the frontend (React)
cd client
npm run dev
The React app runs on http://localhost:5173

## Features Implemented
🧩 Core Functionality

Real-time messaging using Socket.io

Multiple chat rooms: general, sports, and tech

Private messaging between users

Delivery acknowledgments (⏳ pending → ✅ delivered)

Message read tracking (read receipts)

Responsive UI Optimized for mobile & desktop using Tailwind CSS

Message Search Allows keyword-based search via /api/search

### 🧱 Technical Stack
Backend:

Node.js + Express.js

Socket.io

In-memory message storage

REST endpoints for message pagination and search

Frontend:

React 18

Tailwind CSS

Socket.io Client

Responsive layout for mobile and desktop


## Project Structure

socketio-chat/
├── client/                 # React front-end
│   ├── public/             # Static files
│   ├── src/                # React source code
│   │   ├── components/     # UI components
│   │   ├── context/        # React context providers
│   │   ├── hooks/          # Custom React hooks
│   │   ├── pages/          # Page components
│   │   ├── socket/         # Socket.io client setup
│   │   └── App.jsx         # Main application component
│   └── package.json        # Client dependencies
├── server/                 # Node.js back-end
│   ├── config/             # Configuration files
│   ├── controllers/        # Socket event handlers
│   ├── models/             # Data models
│   ├── socket/             # Socket.io server setup
│   ├── utils/              # Utility functions
│   ├── server.js           # Main server file
│   └── package.json        # Server dependencies
└── README.md               # Project documentation

## application screenshot
<img width="1920" height="1080" alt="app screenshot" src="https://github.com/user-attachments/assets/a15f9866-8909-460e-a4c1-9ff783f9d68b" />

