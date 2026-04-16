# 🎥 Video Walkthrough Script - Flashcard Engine

**Total Duration: 4-5 minutes**

---

## 🎬 INTRO (0:00 - 0:30)

"Hi! I'm **Akash Chaudhary**, a final-year B.Tech IT student.

For the Cuemath AI Builder Challenge, I chose Problem 1: The Flashcard Engine.

The goal was not just to convert PDFs into flashcards, but to build a complete intelligent learning system using AI and spaced repetition.

Let me walk you through what I’ve built."

---

## 📱 DEMO PART 1: The User Experience (0:30 - 2:30)

### Registration & Dashboard

"First, let’s create an account."

"And we’re in! This is the dashboard where users can track their progress and manage decks."

---

### Creating a Deck & Uploading PDF

"I’ll create a new deck and upload a PDF."

"This can be any study material — textbooks, notes, or research papers."

"Now let’s generate flashcards using AI."

---

### Card Generation Results

"Flashcards are generated successfully.

Here’s what makes it powerful:

* I implemented a RAG-based system
* It splits content intelligently using semantic chunking
* Maintains context using overlapping chunks
* Generates high-quality questions covering concepts and examples

So instead of random cards, we get meaningful learning content."

---

### Studying Cards

"Now let’s start studying."

"I can either flip directly or try answering first for active recall."

"This improves retention significantly."

"Now here’s the key innovation — time tracking."

"The system tracks how long I take to answer and suggests difficulty automatically."

* Under 8 seconds → Easy
* 8–25 seconds → Medium
* Above 25 seconds → Hard

"This removes guesswork and makes learning data-driven."

---

## 📊 DEMO PART 2: Progress & Analytics (2:30 - 3:30)

### Progress Dashboard

"After studying, I can track my progress."

"It shows mastery levels, streaks, weak areas, and activity charts."

---

### Time Analytics

"This is my favorite feature."

"Cards are categorized based on response time — fast, medium, slow."

"This helps identify what I truly understand vs what needs practice."

---

### UI Experience

"The app also includes multiple themes, smooth animations, and a clean UI."

"It’s designed to make studying engaging and not boring."

---

## 💻 DEMO PART 3: Technical Deep Dive (3:30 - 4:30)

### Card Generation System

"I improved card quality using better prompts and validation."

"Each card goes through checks to avoid incomplete or low-quality content."

---

### RAG Engine

"I implemented semantic chunking with overlap to maintain context."

"This ensures the AI generates meaningful and complete flashcards."

---

### Spaced Repetition

"I used the SM-2 algorithm, similar to Anki."

"It schedules reviews intelligently based on performance."

---

### Architecture

"The system is built using:

* FastAPI for backend
* React + TypeScript for frontend
* Groq API for AI generation
* SQLite / PostgreSQL for database

The application is fully deployable and scalable."

---

## 🚀 CONCLUSION (4:30 - 5:00)

"So what makes this project special?

1. High-quality AI-generated flashcards
2. Active recall learning system
3. Time-based performance tracking
4. Smart difficulty suggestions
5. Clean and engaging UI
6. Proven spaced repetition algorithm

This project demonstrates my ability to build a full-stack AI-powered application from scratch.

With more time, I would add features like collaboration, mobile support, and gamification.

Thank you for watching!"
