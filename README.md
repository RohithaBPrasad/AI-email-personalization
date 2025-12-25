# AI Email Personalization System

An AI-driven email personalization platform that generates targeted marketing emails using agent-based architecture and evaluates campaign performance through A/B testing.

---

## 🚀 Features

- Personalized email generation based on customer profile and campaign context
- Agent-based design for segmentation, subject generation, copywriting, and evaluation
- A/B variant generation with performance-based selection
- Email engagement tracking (opens and clicks)
- Modular backend (FastAPI) and frontend (React)

---

## 🧠 System Architecture

### Backend (FastAPI)
- **Segmentation Agent** – Categorizes customers based on profile data
- **Subject Agent** – Generates email subject lines using LLM prompts
- **Copywriter Agent** – Generates personalized email content
- **Evaluator Agent** – Scores email quality
- **Variant Agent** – Chooses the better A/B variant based on performance

### Frontend (React)
- Email generation interface
- Variant-wise email preview
- Manual tracking of opens and clicks
- Clean, component-based UI

## 🧪 A/B Testing Workflow

1. Two variants (A & B) are generated per campaign
2. Each variant is logged with engagement data
3. Variant selection is based on historical open and click rates
4. System converges toward the higher-performing variant

---

## 🛠 Tech Stack

- **Backend:** Python, FastAPI, MySQL
- **Frontend:** React, JavaScript
- **AI / LLM:** Groq (LLaMA 3.1)
- **Database:** MySQL
- **Architecture:** Agent-based design
