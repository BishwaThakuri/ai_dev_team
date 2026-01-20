# Local Multi-Agent Software Development Team

**Current Status:** Phase 1 (Environment Setup & Architecture)

## 📖 Overview
This project is an **Autonomous AI Agent System** designed to simulate a software engineering team. It runs entirely locally using open-source LLMs, ensuring 100% privacy and zero cost.

The system utilizes **CrewAI** for agent orchestration and **Ollama** to serve the `DeepSeek-Coder` (or `Llama 3`) model.

## 🤖 The "Team" (Planned)
The system consists of two specialized agents:
1.  **Senior Python Developer:** Writes clean, efficient, and PEP8-compliant code.
2.  **Code Reviewer:** Analyzes code for logic errors, security vulnerabilities, and style violations.

## 🛠️ Tech Stack
-   **Orchestration:** CrewAI
-   **LLM Serving:** Ollama (Local API)
-   **Model:** DeepSeek-Coder-V2 (6.7B) / Llama-3
-   **Language:** Python 3.10+

## 🚀 Setup (Phase 1)
1.  Clone the repository.
2.  Install dependencies: `pip install -r requirements.txt`
3.  Set up environment variables in `.env`.
4.  Ensure Ollama is running locally.

---
*This project is currently under active development.*