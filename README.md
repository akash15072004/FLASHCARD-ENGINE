# 🧠 Flashcard Engine

An intelligent flashcard application that transforms PDFs into comprehensive study decks using AI, with spaced repetition and progress tracking.

---

## 👨‍💻 Developed By

**Akash Chaudhary**
🎓 B.Tech Final Year (Information Technology)
💻 Full Stack Developer | React | FastAPI | AI Enthusiast

---

## 🚀 About Me

I am a final-year B.Tech IT student passionate about building scalable full-stack applications and integrating AI into real-world solutions.
This project showcases my ability to design and develop an end-to-end system using modern technologies like FastAPI, React, and AI APIs.

---

## 🌐 Live Demo

### 🚀 Frontend (Vercel)
👉 https://flashcard-engine-steel.vercel.app

### ⚙️ Backend API (Render)
👉 https://flashcard-engine-qflr.onrender.com

### 📘 API Docs (Swagger)
👉 https://flashcard-engine-qflr.onrender.com/docs

## ✨ Features

### 🎯 Core Functionality

* **PDF to Flashcards**: Upload any PDF and automatically generate comprehensive flashcards
* **RAG-Powered Generation**: Semantic chunking ensures thorough coverage (237 cards from 8972 words)
* **Spaced Repetition**: SM-2 algorithm schedules reviews based on your performance
* **Time-Based Analytics**: Track how long you spend on each card to identify mastery levels
* **Active Recall**: Type your answer before revealing to test true understanding

---

### 📊 Progress Tracking

* **Mastery Dashboard**: Track cards across 4 stages (New → Learning → Review → Mastered)
* **Streak Counter**: Build daily study habits with streak tracking 🔥
* **Weak Areas**: Automatically identifies decks that need more attention
* **Activity Charts**: Visualize your study patterns over the last 7 days
* **Time Analytics**: See which cards are quick (mastered) vs slow (need practice)

---

### 🎨 User Experience

* **Simplified Feedback**: 3 clear options (Hard/Medium/Easy) with smart suggestions
* **Dark Mode**: Toggle between light and dark themes
* **Real-time Search**: Find decks and cards instantly
* **Mobile Responsive**: Study anywhere on any device
* **Smooth Animations**: Delightful transitions and card flips

---

## 🚀 Quick Start

### Prerequisites

* Python 3.8+
* Node.js 16+
* Groq API Key ([Get one free](https://console.groq.com))

### Local Development

#### Backend Setup

```bash
cd backend

# Create virtual environment
python -m venv .venv
.venv\Scripts\activate  # On Windows

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp .env.example .env
# Edit .env and add your GROQ_API_KEY

# Create test user (optional)
python create_test_user.py

# Start server
python -m uvicorn main:app --reload --host 0.0.0.0 --port 8000
```

Backend will be available at `http://localhost:8000`

---

### Frontend Setup

```bash
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

Frontend will be available at `http://localhost:5173`

---

## 🌐 Deployment

### Backend (Render)

1. Create a new Web Service on Render
2. Connect your GitHub repository
3. Configure:

   * Root Directory: `backend`
   * Build Command: `pip install -r requirements.txt`
   * Start Command: `uvicorn main:app --host 0.0.0.0 --port $PORT`
4. Add environment variables:

   * GROQ_API_KEY
   * JWT_SECRET
   * FRONTEND_URL
  
---

### Frontend (Vercel)

1. Import project on Vercel
2. Configure:

   * Root Directory: `frontend`
   * Framework: Vite
3. Add environment variable:

   * VITE_API_URL

---

## 🔑 Test Credentials

```
Email: a@gmail.com
Password: 123456
```

---

## 📖 Usage Guide

### Creating a Deck

1. Click **"New Deck"** button
2. Enter deck name and description
3. Upload PDF OR enter topic
4. Generate flashcards

---

### Studying Cards

* Read → Think → Flip → Rate
* Difficulty: Hard / Medium / Easy

---

### Tracking Progress

* Monitor mastery levels
* Check weak areas
* Analyze performance

---

## 🏗️ Architecture

### Tech Stack

**Backend**

* FastAPI
* SQLAlchemy
* SQLite
* Groq API
* PyPDF2

**Frontend**

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
│   ├── database/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── main.py
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── lib/
│   │   └── App.tsx
│   ├── package.json
│   └── vite.config.ts
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
4. Study using spaced repetition
5. Track performance

---

## 🎯 Problem Statement

Convert static PDFs into interactive learning using AI and spaced repetition.

---

## 📊 Results

* 🚀 Efficient AI-based flashcard generation
* 📈 Improved retention
* 🧠 Smart learning tracking

---

## 🔮 Future Enhancements

* Mobile app
* Collaboration
* Gamification
* AI hints

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
