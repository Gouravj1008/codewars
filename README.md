# Code Wars Kids 👾

A kid-friendly coding challenge platform built with the **MERN stack**.

## Features

- Colorful, playful UI designed for kids.
- List of beginner-friendly coding challenges.
- Built-in code editor area.
- Run code via **Judge0 API** (configure your API key).
- Simple real-time collaboration using **websockets (socket.io)**:
  - See when other kids are viewing the same challenge.
  - Share live code changes.

## Project Structure

- `backend/` — Node.js + Express + Socket.io API server
- `frontend/` — React-based frontend

---

## 🔧 Setup Instructions

### 1️⃣ Backend

```bash
cd backend
npm install
cp .env.example .env
# Edit .env and add your JUDGE0 details
npm start
```

### 2️⃣ Frontend

```bash
cd frontend
npm install
npm start
```

Make sure the backend runs on **http://localhost:4000**  
The frontend is configured to talk to it by default.
