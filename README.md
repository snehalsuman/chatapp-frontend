# 💬 SociaLink Frontend

This directory contains the **frontend application** for **SociaLink**, a real-time chat platform built with React.

---

## 🌐 Overview

The frontend offers a sleek, responsive interface for the SociaLink chat system. It handles:

- 🔐 User authentication
- 📡 Real-time messaging
- 🗂️ Message history
- 👤 Profile management
- 📎 File uploads

---

## ✨ Features

- ⚡ Real-time messaging with **Socket.IO**
- 🔐 Secure auth with **HTTP-only cookies**
- 📱 Fully responsive **Tailwind CSS** design
- 🌙 Light/Dark mode toggle
- 🖼️ Image upload & sharing (via Cloudinary)
- 🟢 Online/offline status indicators
- 📜 Chat history with pagination
- 🧑‍💼 Profile editing
- 🌍 Cross-domain communication support

---

## 🛠 Tech Stack

- **React** – UI Library
- **Zustand** – Global State Management
- **Socket.IO Client** – Real-time WebSocket Communication
- **Axios** – API Calls
- **React Router** – Client-side Routing
- **Tailwind CSS** – Utility-first CSS Framework
- **React Hot Toast** – Toast Notifications
- **Cloudinary** – Image Hosting and Management

---

## 📁 Project Structure

/src
├── components # Reusable UI components
├── pages # Page-level components
├── lib # Configs and utilities
├── store # Zustand state logic
├── hooks # Custom React hooks
└── assets # Static files (images/icons)

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Install dependencies

```bash
npm install
2. Setup .env file
Create a .env file in the root of frontend:

env
Copy
Edit
VITE_API_URL=http://localhost:3000/api
3. Start the development server
bash
Copy
Edit
npm run dev
4. Build for production
bash
Copy
Edit
npm run build
📦 Deployment
The frontend is currently live on Vercel:

🌐 https://socialink-chat.vercel.app/

⚠️ Note
To function properly, this frontend requires the SociaLink backend server to be running.

👨‍💻 Author
Built with ❤️ by [Your Name]
GitHub: @yourusername
