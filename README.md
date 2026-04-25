# 🎯 Face Attendance System

A simple full-stack Face Recognition Attendance System.

* ⚛️ Frontend: Next.js
* 🟢 Backend: Node.js + Express

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/face-attendance-system.git
cd face-attendance-system
```

---

## 📦 Install dependencies (one-time)

```bash
cd backend && npm install && cd ../frontend && npm install
```

---

## 🔐 Environment Setup

### Backend

Create a file:

```
backend/.env
```

Add:

```
PORT=5000
```

---

### Frontend

Create a file:

```
frontend/.env.local
```

Add:

```
NEXT_PUBLIC_API_URL=http://localhost:5000/api
```

---

## ▶️ Run the app

### Start backend

```bash
cd backend
npm start
```

---

### Start frontend (new terminal)

```bash
cd frontend
npm run dev
```

---

## 🌐 Open in browser

```
http://localhost:3000
```

---

## ⚠️ Important

* Backend must be running before frontend
* API URL must include `/api`

Correct:

```
http://localhost:5000/api
```

---

## 💡 If this helped

Drop a ⭐ on the repo — it helps more than you think
