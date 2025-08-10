# LogAI

> AI-powered Python logging handler with RAG-based error analysis and Telegram alerts.

LogAI is an **open-source Python package** that turns your application logs into a real-time debugging companion.  
When an error occurs, LogAI uses **Retrieval-Augmented Generation (RAG)** to pull relevant log context and feed it to an AI model, producing human-friendly explanations of what failed and why.  
It then starts a conversation in **Telegram** so engineers can ask follow-up questions, dig deeper into past logs, and troubleshoot collaboratively — without digging through endless log files.

---

## 🚀 Features
- 📝 **Log ingestion** – Plug-and-play logging handler for Python apps.
- 🔍 **RAG-powered context** – Retrieves related logs to give the AI full incident context.
- 🤖 **AI analysis** – Summarizes the issue, likely cause, and suggested fixes.
- 💬 **Telegram integration** – Instant alerts and interactive Q&A.
- ⚡ **Open-source & extensible** – Bring your own vector DB, AI model, or chat platform.

---

## 📦 Installation
```bash
pip install logai
