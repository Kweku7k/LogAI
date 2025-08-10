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
