# 🎯 Face Attendance System

A full-stack Face Recognition Attendance System built with:

* ⚛️ Frontend: Next.js
* 🟢 Backend: Node.js + Express
* 📊 Data Storage: Excel (`data.xlsx`)

---

## 🚀 Features

* Face-based attendance tracking
* Backend API for managing attendance
* Excel-based lightweight database
* Clean full-stack architecture

---

## 📁 Project Structure

```
face-attendance-system/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   ├── package.json
│   └── .env.example
│
├── frontend/
│   ├── app/
│   ├── components/
│   ├── lib/
│   ├── public/
│   ├── package.json
│   └── next.config.ts
│
└── README.md
```

---

## ⚙️ Setup Instructions

### 🔹 1. Clone the repository

```bash
git clone https://github.com/AnshSharma10903/face-attendance-system-.git
cd face-attendance-system-
```

---

## 🔹 2. Setup Backend

```bash
cd backend
npm install
```

### Create `.env` file

Create a file named `.env` in the backend folder:

```
PORT=5000
```

### Run backend

```bash
npm start
```

Backend will run on:
👉 http://localhost:5000

---

## 🔹 3. Setup Frontend

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on:
👉 http://localhost:3000

---

## 🔗 API Connection

Make sure frontend connects to backend:

```
http://localhost:5000
```

You can configure this using:

```
NEXT_PUBLIC_API_URL=http://localhost:5000
```

---

## 📦 Requirements

* Node.js (v18 or higher recommended)
* npm

---

## ⚠️ Important Notes

* Do NOT upload `.env` files
* Do NOT upload `node_modules`
* Excel file (`data.xlsx`) is used as database
* Backend must run before frontend

---

## 🧪 Running the Project

1. Start backend
2. Start frontend
3. Open browser at http://localhost:3000

---

## 📌 Future Improvements

* Replace Excel with database (MongoDB / PostgreSQL)
* Add authentication system
* Improve face recognition accuracy
* Deploy to cloud

---

## 👨‍💻 Author

Ansh Sharma

---

## ⭐ If you like this project

Give it a star on GitHub ⭐
