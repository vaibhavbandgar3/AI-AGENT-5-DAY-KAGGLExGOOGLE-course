# AI-AGENT-5-DAY-KAGGLExGOOGLE-course
# 🚀 HR Lifecycle Automation Agent

**AI-powered automation of screening, scheduling, onboarding, performance reviews, and offboarding using a single Gemini LLM agent.**
Built as part of the **Google × Kaggle 5-Day AI Agents Intensive**.

---

## 📌 Overview

This project automates the entire HR lifecycle using one unified AI agent.
It replaces repetitive manual HR tasks with intelligent, end-to-end workflows that can reason, act, and generate structured outputs.

---

## 🧠 Features

* **Resume Screening** → score, matched skills, fit label
* **Parallel Screening** → high-volume hiring support
* **Iterative Refinement Loop** → shortlisting automation
* **Interview Scheduling** → auto-generated time slots
* **Onboarding Plan Generator** → 7-day personalized plan
* **Offboarding Workflow** → checklist + knowledge transfer
* **Performance Review Agent** → summary, strengths, goals
* **Tools** → code executor + search
* **Memory System** → in-memory + persistent
* **A2A Service Exposure** → agent callable via API
* **MCP Component Registry** → modular agent functions
* **Metrics Dashboard** → strong-fit % + JD coverage

---

## 🏗️ Architecture

```
Global Gemini Agent
       │
       ├── Screening Component
       ├── Onboarding Component
       ├── Offboarding Component
       ├── Performance Component
       ├── Scheduling Component
       │
Tools → Search Tool, Code Execution Tool
Memory → In-Memory + Persistent Store
A2A API → External integrations
MCP → Component registry & router
```

---

## 📁 Project Structure

```
HR_Lifecycle_Agent.ipynb        # Main notebook
data/
 ├── memory_store.json          # Persistent memory store
 └── people_demo.csv            # Demo dataset
```

---

## ▶️ How to Run

1. Open **Kaggle Notebook**
2. Upload `HR_Lifecycle_Agent.ipynb`
3. Add your `GOOGLE_API_KEY` in *Kaggle Secrets*
4. Run the notebook top to bottom
5. Test workflows with sample calls at the end

---

## 🖥️ Demo Capabilities

* Run sequential and parallel screening
* Auto-generate onboarding/offboarding documents
* Produce performance reviews
* Call workflows via A2A API
* Visualize metrics using charts

---

## 🔧 Tech Stack

* Python
* Google ADK (Agents Development Kit)
* Gemini 2.5 Pro
* Pandas
* Matplotlib
* FastAPI + Uvicorn (optional A2A)
* Concurrent Futures

---

## 🌱 Future Enhancements

* Real calendar & email API integration
* HRIS integration (Workday, SAP, Greenhouse)
* Vector memory + embeddings search
* Unified HR analytics dashboard
* Multi-agent orchestration

---
