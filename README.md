# 🤖 Agentic AI Fact Checker – CrewAI Multi-Agent System
Agentic AI fact-checking system using CrewAI multi-agent architecture with LLM-based reasoning, verification, and structured outputs.

[![Python](https://img.shields.io/badge/Python-3.10-blue)]()
[![LLM](https://img.shields.io/badge/LLM-OpenAI%20%7C%20CrewAI-purple)]()
[![CrewAI](https://img.shields.io/badge/CrewAI-Multi--Agent-orange)]()
[![Status](https://img.shields.io/badge/Project-Completed-brightgreen)]()
[![License](https://img.shields.io/badge/License-MIT-lightgrey)]()

👤 Author: Nuru Siraj Mohammed  
🤖 Machine Learning & AI Graduate – Smart AI LLC  

---

## 📖 Project Overview

This project implements an **Agentic AI Fact-Checking System** using **CrewAI**, where multiple intelligent agents collaborate to verify the accuracy of claims.

The system simulates a **real-world fact-checking pipeline**, combining:
- Large Language Models (LLMs)
- Multi-agent reasoning
- Tool usage (search, verification)
- Autonomous decision-making

---

## 🎯 Objectives

- Build an **AI-driven fact-checking system**
- Design **collaborative intelligent agents**
- Automate claim verification using external knowledge
- Improve reliability of AI-generated information
- Demonstrate agentic workflows (reasoning + acting)

---

## 🧠 System Architecture

### 🔹 Multi-Agent Design

| Agent Role        | Responsibility |
|------------------|---------------|
| 🔍 Research Agent | Searches for relevant information |
| 🧠 Analyst Agent  | Evaluates evidence |
| 🧾 Verifier Agent | Cross-checks facts |
| 📝 Reporter Agent | Generates final verdict |

---

## ⚙️ Workflow

1. User submits a claim  
2. Research Agent gathers information  
3. Analyst Agent evaluates credibility  
4. Verifier Agent confirms accuracy  
5. Reporter Agent produces structured output  

---

## 🏗️ Project Structure
agentic-ai-fact-checker-crewai/
│
├── src/
│ ├── agents.py
│ ├── tasks.py
│ ├── tools.py
│ ├── main.py
│
├── data/
│
├── results/
│ ├── sample_outputs.json
│ ├── workflow_diagram.png
│
├── requirements.txt
└── README.md


---

## 🤖 Technologies Used

- CrewAI (Multi-Agent Framework)
- OpenAI / LLM APIs
- Python
- LangChain (optional tools integration)

---

## 📊 Sample Output

```json
{
  "claim": "The Great Wall of China is visible from space",
  "verdict": "False",
  "confidence": 0.92,
  "evidence": [
    "NASA states it is not visible to the naked eye from space",
    "Astronaut reports confirm limited visibility"
  ],
  "explanation": "The claim is a common myth..."
}
📈 Results & Performance

✔ Accurate fact-checking on multiple test claims

✔ Multi-agent collaboration improves reasoning

✔ Structured outputs enhance interpretability

✔ Reduced hallucination compared to single-agent systems
