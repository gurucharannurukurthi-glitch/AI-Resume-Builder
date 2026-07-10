# 🚀 AI Resume Builder

An AI-powered Resume Builder that helps users create professional, ATS-friendly resumes using **Google Gemini AI**. Users can sign in with Google, build resumes using multiple templates, receive AI-powered content suggestions, track resume versions, and export resumes as PDF.

## 🌐 Live Demo

**Frontend:** https://ai-resume-builder-ychp.vercel.app

**Backend API:** https://ai-resume-builder-k3pi.onrender.com

---

# ✨ Features

- 🔐 Google OAuth Authentication
- 📄 Create and edit resumes
- 🤖 AI-powered resume suggestions using Google Gemini
- 📊 ATS Score Analysis
- 📈 Resume Version History
- 🎨 Multiple Resume Templates
- 📥 Export Resume as PDF
- ☁️ MongoDB Atlas Database
- 🌐 Fully deployed using Vercel & Render

---

# 🛠 Tech Stack

## Frontend

- React.js
- Vite
- React Router
- Context API
- React Hot Toast

## Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Google OAuth
- JWT Authentication

## AI

- Google Gemini API

## Deployment

- Vercel
- Render

---

# 📁 Project Structure

```
AI-Resume-Builder
│
├── client
│   ├── src
│   ├── public
│   └── package.json
│
├── server
│   ├── src
│   │   ├── config
│   │   ├── controllers
│   │   ├── middleware
│   │   ├── models
│   │   ├── routes
│   │   ├── services
│   │   └── utils
│   ├── package.json
│   └── server.js
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/gurucharannurukurthi-glitch/AI-Resume-Builder.git

cd AI-Resume-Builder
```

---

## Backend Setup

```bash
cd server

npm install

npm start
```

---

## Frontend Setup

```bash
cd client

npm install

npm run dev
```

---

# 🔑 Environment Variables

## Backend (.env)

```env
PORT=5000

MONGODB_URI=YOUR_MONGODB_URI

JWT_SECRET=YOUR_SECRET

JWT_EXPIRES_IN=7d

CLIENT_URL=http://localhost:5173

GOOGLE_CLIENT_ID=YOUR_GOOGLE_CLIENT_ID

GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

---

## Frontend (.env)

```env
VITE_API_URL=http://localhost:5000/api

VITE_GOOGLE_CLIENT_ID=YOUR_GOOGLE_CLIENT_ID
```

---

# 📸 Screenshots

> Add screenshots here

- Home Page
- Dashboard
- Resume Builder
- AI Suggestions
- ATS Score
- Version History
- PDF Preview

---

# 🚀 Future Improvements

- Resume sharing via URL
- Collaborative editing
- AI Interview Preparation
- Cover Letter Generator
- Grammar checking
- Additional templates
- Dark Mode

---

# 👨‍💻 Author

**Guru Charan**

GitHub

https://github.com/gurucharannurukurthi-glitch

LinkedIn

(Add your LinkedIn profile here)

---

# ⭐ If you like this project

Give this repository a ⭐ on GitHub.
