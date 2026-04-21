# 🚀 Flispark

Flispark is a SaaS language learning platform that helps users learn vocabulary through flashcards, testing, and AI-generated exercises.
It focuses on turning raw content into structured learning materials (e.g. generating tests from text).

---

## 🔥 What is Flispark?

Flispark combines:

- Flashcards for vocabulary learning
- AI-powered test generation (Text-to-Test)
- Multiple learning modes (Multiple Choice Question, True/False, Active Recall, Audio)
- Subscription-based SaaS model

The system is designed to automate content creation and make learning more interactive.

👉 Flispark is live at https://flispark.com

#### 🚧 UI is currently being redesigned — updated visuals coming soon

## 🎬 Project Showcase

[![Watch the demo](https://img.youtube.com/vi/wcJLvcIAj_8/hqdefault.jpg)](https://www.youtube.com/watch?v=wcJLvcIAj_8)

Short demo of FliSpark features and UI.

## 🧠 Key Features

- AI-based flashcard generation with contextual examples
- Text-to-Test: generate quizzes from raw text
- Multiple learning modes (Multiple Choice, True/False, Active Recall, Audio)
- Spaced repetition system
- Secure authentication (NextAuth, JWT, email verification)
- Stripe subscriptions & payments
- Image search with fallback strategy (Google → GIPHY → Tenor → Reddit)
- File uploads via Backblaze B2

## 🏗 System Overview

Flispark is built as a modern full-stack SaaS application:

- **Frontend:** Next.js, TypeScript, Tailwind CSS, Shadcn UI
- **Backend:** Next.js (API routes)
- **Auth:** NextAuth.js (OAuth, sessions, JWT)
- **Payments:** Stripe
- **Storage:** Backblaze B2, PostgreSQL
- **AI:** Google Gemini API
- **External APIs:** Google, Reddit, GIPHY, Tenor, Backblaze B2

## ⚙️ Engineering Highlights

- Implemented fallback system for unreliable external APIs
- Built authentication flow with NextAuth (OAuth, sessions, email verification)
- Integrated Stripe subscriptions with webhook validation
- Designed AI pipeline for generating learning content
- Optimized queries and caching strategies
- Handled edge cases (timeouts, API failures, retries)

## 🧩 Architecture Philosophy

- Separation of concerns (auth, payments, AI, storage)
- Monolithic fullstack architecture (Next.js)
- Resilient API design with fallback strategies
- Security-first approach (no trust on client-side)

## 🔒 Note

The main production codebase is private due to sensitive business logic and API keys.

This repository is intended to showcase architecture, features, and system design.

## 👨‍💻 Author

Full-stack developer focused on building modern SaaS applications with Next.js, TypeScript, and AI integrations.
