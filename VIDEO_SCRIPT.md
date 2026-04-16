# 🧠 Flashcard Engine

An intelligent flashcard application that transforms PDFs into comprehensive study decks using AI, with spaced repetition and progress tracking.

---

## 👨‍💻 Developed By

**Akash Chaudhary**
🎓 B.Tech Final Year (Information Technology)
💻 Full Stack Developer | React | FastAPI | AI Enthusiast

---

## ✨ Features

### 🎯 Core Functionality

* **PDF to Flashcards**: Upload any PDF and automatically generate flashcards
* **AI-Powered Generation**: Uses Groq API for smart question-answer creation
* **Spaced Repetition**: SM-2 algorithm schedules reviews efficiently
* **Active Recall**: Type your answer before revealing the solution
* **Time-Based Analytics**: Measures response time for better learning

---

### 📊 Progress Tracking

* **Mastery Dashboard**: Track learning stages (New → Learning → Review → Mastered)
* **Streak Counter**: Maintain daily study consistency 🔥
* **Weak Areas Detection**: Focus on topics needing improvement
* **Activity Charts**: Visualize progress over time
* **Performance Insights**: Identify strong and weak concepts

---

### 🎨 User Experience

* **Simple Feedback System**: Hard / Medium / Easy
* **Dark Mode Support**
* **Real-time Search**
* **Responsive Design**
* **Smooth Animations**

---

## 🚀 Quick Start

### 📌 Prerequisites

* Python 3.10+
* Node.js 16+
* Groq API Key

---

## ⚙️ Local Development

---

### 🔹 Backend Setup (FastAPI)

```bash
cd backend

# Create virtual environment
python -m venv .venv
.venv\Scripts\activate   # Windows

# Install minimal dependencies (recommended)
pip install fastapi uvicorn python-multipart

# Run server
python -m uvicorn main:app --reload --port 8000
```

👉 Backend: http://localhost:8000

---

### 🔹 Frontend Setup (Vite + React)

```bash
cd frontend

npm install
npm run dev
```

👉 Frontend: http://localhost:5173

---

## 🔑 Environment Variables

Create `.env` inside backend:

```
GROQ_API_KEY=your_api_key
JWT_SECRET=your_secret
```

---

## 🔧 Important Fixes (Based on Real Setup Issues)

* ❌ Do NOT use `app/api/upload/route.ts` (Next.js only)
* ✅ This project uses **Vite + FastAPI**
* ⚠️ Install dependencies step-by-step (avoid heavy installs first)
* ⚠️ Ensure backend is running before frontend (else "Failed to fetch")

---

## 🏗️ Architecture

### 🔹 Backend

* FastAPI
* SQLAlchemy
* SQLite
* Groq API (LLM)
* PDF Processing

### 🔹 Frontend

* React + TypeScript
* Vite
* Tailwind CSS
* Framer Motion
* React Router

---

## 📁 Project Structure

```
flashcard-engine/
├── backend/
│   ├── routes/
│   ├── services/
│   ├── models/
│   ├── main.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── lib/
│   │   └── App.tsx
│   └── package.json
│
└── README.md
```

---

## 🔧 API Endpoints

### Authentication

* POST `/auth/register`
* POST `/auth/login`
* GET `/auth/me`

### Decks

* GET `/decks`
* POST `/decks`
* GET `/decks/{id}`
* DELETE `/decks/{id}`
* POST `/decks/{id}/upload-pdf`
* POST `/decks/{id}/generate`

### Cards

* GET `/cards/deck/{id}`
* POST `/cards/{id}/rate`

---

## 🧪 How It Works

1. Upload PDF
2. Extract text
3. AI generates flashcards
4. User reviews using spaced repetition
5. System tracks progress & performance

---

## 🎯 Problem Statement

This project solves:

* Converting static PDFs into interactive learning
* Improving retention using spaced repetition
* Making study engaging with analytics and tracking

---

## 📊 Results

* 🚀 Efficient flashcard generation using AI
* 📈 Improved learning retention
* 🧠 Smart difficulty tracking
* ⏱️ Time-based performance insights

---

## 🔮 Future Enhancements

* 📱 Mobile app
* 🤝 Collaborative decks
* 🎮 Gamification
* 🧠 AI hints system

---

## 📝 License

MIT License

---

## 🤝 Contributing

Contributions are welcome!

---

## 📬 Contact

📧 [akashchaudhary5100@gmail.com](mailto:akashchaudhary5100@gmail.com)
📱 9140814285

---

⭐ Built with ❤️ by Akash Chaudhary
