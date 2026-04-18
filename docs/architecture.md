# FliSpark Architecture

## Overview

FliSpark is a full-stack SaaS application built with a modern web architecture, combining AI services, external APIs, and cloud storage.

---

## Tech Stack

### Frontend
- React / Next.js
- TypeScript
- Tailwind CSS

### Backend
- Node.js (API routes / server logic)
- REST APIs for client communication

### Authentication
- JWT-based system
- Access & Refresh tokens
- Secure HTTP-only cookies

### Database
- (Your DB here: MongoDB / PostgreSQL)

### External Services
- Stripe (payments & subscriptions)
- Google API (image search)
- Reddit API (fallback content)
- GIPHY API (fallback content)
- AI API (Gemini / OpenAI)
- Backblaze B2 (file storage)

---

## High-Level Flow

1. User interacts with frontend (Next.js)
2. Frontend sends requests to backend API
3. Backend handles:
   - authentication
   - business logic
   - external API calls
4. Data stored in database / cloud storage
5. Response returned to frontend

---

## Key Concepts

- Modular API design
- Separation of concerns (auth, payments, AI)
- Fallback strategy for unstable APIs
- Scalable SaaS architecture