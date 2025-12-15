# 🚀 Full Stack Application

This repository contains a **cleanly separated Frontend and Backend** setup, designed for scalable and maintainable full‑stack development.

---

## 📂 Project Structure

```txt
root/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middlewares/
│   │   ├── utils/
│   │   └── index.js
│   ├── .env
│   ├── package.json
│   └── nodemon.json
│
├── frontend/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── store/
│   │   ├── services/
│   │   ├── utils/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   ├── package.json
│   ├── vite.config.js
│   └── tailwind.config.js
│
└── README.md
```

---

## 🔧 Backend Setup (Node.js + Express)

### Tech Stack

* Node.js (ES Modules)
* Express.js
* MongoDB (Mongoose)
* JWT Authentication
* Bcrypt (Password Hashing)
* Multer + Cloudinary (File Uploads)
* CORS & Cookie Parser

### Install Dependencies

```bash
cd backend
npm install
```

### Environment Variables (`backend/.env`)

```env
PORT=8000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

### Run Backend

```bash
npm run dev
```

Backend runs on:

```
http://localhost:8000
```

---

## 🎨 Frontend Setup (Vite + React)

### Tech Stack

* React 18
* Vite
* Redux Toolkit + Redux Persist
* React Router DOM
* Tailwind CSS
* Radix UI
* Framer Motion
* Axios

### Install Dependencies

```bash
cd frontend
npm install
```

### Environment Variables (`frontend/.env`)

```env
VITE_API_BASE_URL=http://localhost:5000
```

### Run Frontend

```bash
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 🏗️ Build Frontend

```bash
npm run build
npm run preview
```

---

## 📦 Scripts Summary

### Backend

| Command     | Description                |
| ----------- | -------------------------- |
| npm run dev | Start backend with nodemon |

### Frontend

| Command         | Description           |
| --------------- | --------------------- |
| npm run dev     | Start Vite dev server |
| npm run build   | Production build      |
| npm run preview | Preview build         |
| npm run lint    | Run ESLint            |

---

## ✅ Best Practices

* Keep backend and frontend fully decoupled
* Use environment variables for secrets
* Centralize API calls in frontend services
* Use middleware for authentication & validation
* Maintain reusable UI components

---

## 📄 License

This project is for internal development and learning purposes only.
