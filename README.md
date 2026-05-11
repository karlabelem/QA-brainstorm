# 🛍️ Lyra

An AI-powered tool that helps users make better purchasing decisions by analyzing **product materials** and **customer sentiment**, not just price or ratings.

---

## 🧠 Overview

Online shopping often hides product quality behind branding and marketing. Many products look premium but use low-quality materials, making it difficult for consumers to make informed decisions.

This project aims to answer a simple question:

> **“Is this product actually worth buying?”**

By combining:
- 🧵 Material analysis (e.g. cotton vs polyester)
- ⭐ Customer review insights
- 🤖 AI-generated reasoning

We provide users with a clear, concise recommendation:
- **Buy**
- **Consider**
- **Skip**

---

## 🎯 MVP Scope (v1)

The goal is to build a simple, functional prototype that demonstrates the core idea.

### Input
- Product link **or**
- Pasted product description

### Output
- Recommendation: **Buy / Consider / Skip**
- Short explanation including:
  - Material quality insights
  - Summary of customer sentiment

---

## 🧩 Core Components

- **Input Handler**
  - Accepts product link or raw text

- **Product Parser**
  - Extracts relevant fields (materials, description, etc.)

- **Material Analyzer**
  - Interprets material composition
  - Applies basic quality heuristics

- **AI Reasoning Layer**
  - Combines material insights + text/reviews
  - Generates human-readable explanation

- **Frontend UI**
  - Simple interface for input + results display

---

## 🧵 Focus Area

We are initially focusing on:

> **Clothing products**

Reason:
- Material quality has a strong impact on comfort, durability, and value
- Easy to demonstrate meaningful insights (e.g. polyester vs cotton)

---

## 🚀 Tech Stack (TBD)

- **Frontend:** (e.g. React / Next.js)
- **Backend:** (e.g. FastAPI / Node)
- **AI:** (e.g. OpenAI API)
- **Database:** (optional for MVP)

*(Open to discussion and iteration)*

---

## 👥 Team Roles (TBD)

We will divide work across:
- Frontend
- Backend / API
- AI / prompt logic
- Data / parsing
- Coordination / integration

*(To be finalized as we start building)*

---

## 📅 Development Plan (Draft)

**Week 1**
- Finalize MVP scope
- Set up repo + basic structure
- Implement basic input → output flow

**Week 2**
- Improve material detection
- Refine AI responses
- UI improvements

**Week 3 (Optional)**
- Add review integration
- Improve recommendation quality
- Polish for demo

---

## 🎤 Project Story

This project was created to explore how AI can be used to improve everyday decision-making, specifically in online shopping where product quality is often unclear.

We aim to demonstrate:
- Practical AI integration
- Strong product thinking
- Real-world problem solving

---

## ⚠️ Notes

- This is an **MVP-first project** — keep it simple
- Focus on **shipping something usable**
- Avoid over-engineering early

---

## 📌 Next Steps

- [ ] Finalize MVP scope
- [ ] Decide tech stack
- [ ] Assign roles
- [ ] Set up repo structure
- [ ] Start building 🚀

---

## 💡 Future Ideas (Optional)

- Price tracking
- Alternative product suggestions
- Browser extension
- Expanded categories beyond clothing

---

## 📛 Naming (TBD)

Working title: **“Should I Buy This?”**

*(Open to better name suggestions)*
