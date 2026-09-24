<div align="center">

# 🧪 AI Experiment Planner

### Autonomous Scientific Experiment Planning System

*Generate protocols • Optimize resources • Predict outcomes • Recommend follow-ups*

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org)
[![Gemini](https://img.shields.io/badge/Gemini-API-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://makersuite.google.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

[Features](#-features) • [Tech Stack](#-tech-stack) • [Setup](#-quick-start) • [Architecture](#-architecture) • [Screenshots](#-screenshots)

</div>

---

## 📖 About The Project

**AI Experiment Planner** is an intelligent autonomous system that helps researchers and scientists design, plan, and execute scientific experiments using cutting-edge AI techniques.

It combines **three powerful technologies**:
- 🕸️ **Knowledge Graphs** — to understand relationships between scientific concepts
- 🎯 **Bayesian Optimization** — to find optimal experimental parameters
- 🤖 **Large Language Models (Gemini)** — to generate protocols & predict outcomes

> **Built as a CPU-friendly, practice-level project** — no GPU required, uses Google Gemini's free API tier.

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🧬 Protocol Generation
AI-powered step-by-step experimental protocols with materials, procedures, safety notes, and timelines.

### 📊 Outcome Prediction
Predict experiment results with confidence scores based on historical data + LLM reasoning.

### 🎯 Bayesian Optimization
Automatically find optimal experimental parameters using Gaussian Process + acquisition functions.

</td>
<td width="50%">

### 🕸️ Knowledge Graph
Interactive visualization of relationships between scientific entities (materials, methods, outcomes).

### 💡 Follow-up Recommendations
Smart suggestions for next experiments based on results and knowledge graph traversal.

### 🤖 AI Research Assistant
Chat interface to discuss experiments, ask scientific questions, and get instant insights.

</td>
</tr>
</table>

### Additional Capabilities
- 📈 **Analytics Dashboard** — Real-time metrics and insights
- 💰 **Resource Allocation** — Smart budget & material optimization
- 🔐 **User Authentication** — Secure JWT-based login
- 🌓 **Dark/Light Mode** — Beautiful theme switching
- 📱 **Fully Responsive** — Works on all devices
- 📤 **Export Options** — Download protocols as PDF/JSON

---

## 🛠️ Tech Stack

<table>
<tr>
<td valign="top" width="50%">

### Backend
- **Framework:** FastAPI
- **Language:** Python 3.10+
- **Database:** SQLite / PostgreSQL
- **ORM:** SQLAlchemy + Alembic
- **Validation:** Pydantic
- **Auth:** JWT + Passlib (bcrypt)

### AI & ML
- **LLM:** Google Gemini API
- **Knowledge Graph:** NetworkX
- **Bayesian Opt:** scikit-optimize
- **Numerical:** NumPy, SciPy, Pandas
- **Modeling:** Gaussian Process

</td>
<td valign="top" width="50%">

### Frontend
- **Framework:** React 18
- **Build Tool:** Vite
- **Styling:** Tailwind CSS
- **Routing:** React Router v6
- **State:** Zustand / Redux Toolkit
- **Charts:** Recharts
- **Graph Viz:** React Flow
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **HTTP:** Axios

### DevOps
- **Version Control:** Git + GitHub
- **Testing:** Pytest, React Testing Library
- **API Testing:** Postman
- **Containerization:** Docker (optional)

</td>
</tr>
</table>

---

## 🏗️ Architecture



---

## 🚀 Quick Start

### Prerequisites

Make sure you have these installed:

| Tool | Version | Check Command |
|------|---------|---------------|
| Python | 3.10+ | `python --version` |
| Node.js | 18+ | `node --version` |
| npm | 9+ | `npm --version` |
| Git | Latest | `git --version` |

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishakha2121/autonomous-experiment-planner.git
cd autonomous-experiment-planner

# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate it
# Windows:
venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
copy .env.example .env      # Windows
cp .env.example .env        # Mac/Linux


# Navigate to frontend
cd frontend

# Install dependencies
npm install

# Create .env file
copy .env.example .env      # Windows
cp .env.example .env        # Mac/Linux