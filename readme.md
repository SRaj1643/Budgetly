# 💰 Budgetly

> **Your Intelligent AI-Powered Personal Finance Platform**

<p align="center">

Manage your finances effortlessly with AI, voice commands, multilingual support, powerful analytics, and complete ownership of your data.

</p>

---

## 📖 Overview

Budgetly is a modern, AI-assisted personal finance platform designed to make money management simple, intelligent, and accessible.

Unlike traditional expense trackers, Budgetly allows users to interact naturally using text or voice while maintaining complete control over their financial data.

Whether you want to manually record expenses, ask AI to organize transactions, analyze your spending habits, or receive personalized financial coaching, Budgetly provides a seamless experience without making AI a dependency.

---

## ✨ Key Features

### 💳 Finance Management

- Transaction Management
- Income Tracking
- Expense Tracking
- Budget Planning
- Savings Goals
- Financial Reports
- Calendar View
- Analytics Dashboard
- Multi Currency Support
- Category Management
- Receipt Attachments

---

### 🤖 AI Assistant

A floating AI assistant available across every page.

Capabilities include:

- Add transactions using natural language
- Edit existing transactions
- Delete transactions
- Search transactions
- Navigate the application
- Answer finance-related questions
- Generate financial summaries
- Understand conversational context

Example:

> "Yesterday I spent ₹500 on groceries."

---

### 🧠 AI Coach

A dedicated financial mentor.

Provides:

- Spending Analysis
- Savings Recommendations
- Budget Suggestions
- Monthly Reviews
- Goal Planning
- Personalized Financial Advice

Unlike the AI Assistant, the AI Coach focuses on helping users make smarter financial decisions rather than executing actions.

---

### 🎤 Voice Support

Budgetly supports natural voice interactions.

Initial languages:

- 🇮🇳 Hindi
- 🇬🇧 English

Supported speech patterns:

- English
- Hindi
- Hinglish
- Mixed Hindi + English

Examples:

> "Kal maine ₹500 ki coffee pi."

> "Yesterday I spent ₹1200 on groceries."

> "Aaj salary receive hui."

Voice responses are also supported for AI conversations.

---

### 🌍 Localization

Initial Languages

- English
- Hindi

Future support includes:

- Spanish
- French
- German
- Japanese
- Arabic

---

### 💱 Multi-Currency

Budgetly supports multiple currencies.

Initially:

- INR
- USD
- EUR
- GBP

The preferred currency can be changed at any time.

---

## 🏗 System Architecture

```
Browser
    │
    ▼
Next.js Frontend
    │
    ▼
Backend API
    │
    ▼
Finance Engine
    │
 ┌──┴───────────────┐
 │                  │
 ▼                  ▼
Database        OpenRouter AI
 │
 ▼
Cloud Storage
```

The Finance Engine is the core of Budgetly.

AI never directly modifies the database.

Every AI-generated action passes through validation before execution.

---

## 🛠 Tech Stack

### Frontend

- Next.js
- React
- TypeScript
- Tailwind CSS
- shadcn/ui

### Backend

- Next.js API Routes
- TypeScript

### Database

- PostgreSQL
- Prisma ORM

### Authentication

- Better Auth

### AI

- OpenRouter

### Storage

- Cloudflare R2

### Deployment

- Vercel

---

## 🎯 Design Principles

Budgetly follows several engineering principles:

- AI assists users but never replaces user control.
- Every financial operation is validated before execution.
- Privacy is a first-class concern.
- The system remains functional even if AI services are unavailable.
- Modular architecture allows components to be replaced independently.
- Accessibility and responsiveness are built in from the beginning.

---

## 📂 Project Structure

```
budgetly/

├── app/
├── components/
├── features/
├── lib/
├── prisma/
├── public/
├── docs/
├── tests/
├── middleware.ts
└── README.md
```

---

## 📚 Documentation

Comprehensive documentation is available inside the `docs/` directory.

Documentation includes:

- Product Vision
- Software Requirements Specification
- System Architecture
- Database Design
- API Design
- AI Architecture
- Security
- Deployment
- Development Roadmap
- Coding Standards
- Testing Strategy

---

## 🚀 Development Philosophy

Budgetly is built following professional software engineering practices.

Every feature follows the same lifecycle:

```
Requirement Analysis

↓

Architecture

↓

Database Design

↓

API Design

↓

Frontend Design

↓

Implementation

↓

Testing

↓

Review

↓

Documentation
```

No feature is implemented before being designed.

---

## 🤝 Contributing

Contributions are welcome.

Before contributing, please read:

- Coding Standards
- Architecture Documentation
- Development Roadmap

---

## 📜 License

This project will be released under the MIT License.

---

## ❤️ Vision

Budgetly aims to become a privacy-first, multilingual, AI-powered financial platform that empowers users to manage their finances naturally while retaining complete ownership of their data.

AI is an assistant—not the decision maker.

The user is always in control.
