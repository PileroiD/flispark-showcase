# FliSpark Features

FliSpark is a SaaS language learning platform that combines flashcards, AI, and interactive tests to help users learn languages faster

## Core Features

### 🧠 AI Learning System

- AI-generated flashcards based on user input
- Custom test generation (quizzes, translations)
- Context-aware language explanations
- Automatically generated tests based on user input

### 📚 Flashcards System

- Create and manage personal decks
- Spaced repetition learning logic
- Progress tracking per deck
- AI-generated sentence contexts for each word

![Flashcards System](./screenshots/cards-overview.png)

### 📖 Learning System

- Multiple learning modes for effective vocabulary retention:
    - Multiple Choice
    - True or False
    - Active Recall (writing-based)
    - Audio-based tests (listening + typing)
- Combines recognition and recall-based learning
- Designed to simulate real language usage

### 🧪 Text-to-Test (AI Feature)

- Converts real-world text into personalized learning material
- Detects unknown vocabulary based on user progress
- Filters and selects relevant words automatically
- Generates adaptive tests to reinforce new vocabulary

### 🔐 Authentication System

- Email/password authentication
- Access & refresh token system
- Email verification flow
- Protected routes for authenticated users

### 💳 Payments & Subscriptions

- Stripe integration for subscriptions
- In-app currency system
- Payment-based feature unlocking

### 🖼 Image Search System

- Search images by keywords
- Google Search Engine API integration
- Fallback system:
    - GIPHY API
    - Tenor API
    - Reddit API
- Timeout handling for failed requests

### ☁ File Uploads

- User image uploads
- Cloud storage using Backblaze B2

## Goal

To create an AI-powered, interactive, and scalable language learning experience.
