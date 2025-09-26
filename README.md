### 📘 Agentic AI Approach – Multi-Agent PDF Analysis
## 🚀 Overview

This project demonstrates an agentic AI approach using CrewAI (CRU-A) and OpenAI API to perform intelligent PDF analysis.

The system is designed around a multi-agent architecture:

Each agent is responsible for analyzing one PDF.

A manager agent coordinates the flow, collects insights from each agent, and synthesizes the final response.

The system can answer questions based on the content of multiple PDFs combined.

### ✨ Features

📄 PDF Analysis – Upload multiple PDFs (3 in this case) for contextual QA.

🤖 Multi-Agent Workflow – Each agent specializes in one PDF, while the manager integrates their results.

🔍 Question Answering – Ask a question, and the agents collaborate to generate an answer.

### 🧠 Agent Roles –

Agent 1 → Analyzes PDF #1

Agent 2 → Analyzes PDF #2

Agent 3 → Analyzes PDF #3

Manager Agent → Collects findings and generates final response.

### 🛠️ Tech Stack

CrewAI
 – for multi-agent orchestration

OpenAI API
 – for LLM-powered analysis

Python (backend logic)

PDF processing libraries (e.g., PyPDF2 / pypdf)
