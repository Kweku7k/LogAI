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

## 🛡 License
This project is licensed under the MIT License – see the LICENSE file for details.

---

## 🌍 Community
Join our engineer chat on Telegram: https://t.me/elonvibecoders

## 📅 Roadmap (MVP – 4 Weeks)
  - Week 1: Repo setup, log ingestion scaffolding, vector DB connection.
  - Week 2: Log retrieval via RAG, error trigger rules.
  - Week 3: AI integration & Telegram bot.
  - Week 4: Polishing, examples, v0.1.0 release.

# Contributing to LogAI

🎉 First off, thanks for taking the time to contribute! This project thrives on community effort.

---

## 📌 How You Can Contribute
- 🐛 **Report bugs** – Found something broken? Let us know.
- 💡 **Suggest features** – Got ideas for improvement? Open a discussion or issue.
- 🛠 **Fix bugs & add features** – Pick an issue and start coding.
- 📖 **Improve documentation** – Even small doc fixes are valuable.

---

## 🧩 Getting Started

1. **Fork the repository**
   - Click the **Fork** button at the top right of the repo page.

2. **Clone your fork**
   ```bash
   git clone https://github.com/kweku7k/logai.git
   cd logai
   ```
3.	Set up the development environment
  ``` bash
  python -m venv env
  source env/bin/activate   # On Windows: env\Scripts\activate
  pip install -r requirements.txt
  pip install -r requirements-dev.txt
  ```

4.	Create a feature branch
  ```bash
  git checkout -b feature/my-new-feature
  ```

5.	Commit changes
  ```bash
  git add .
  git commit -m "feat: add my new feature"
  ```

6.	Push branch & open PR
  ```bash
  git push origin feature/my-new-feature
  ```

## ✅ Contribution Guidelines
Follow PEP8 style guide.
•	Run tests before pushing:
``` bash
pytest
```


