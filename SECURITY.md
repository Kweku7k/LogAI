# Security Policy

## 📢 Reporting a Vulnerability

If you discover a security vulnerability in **LogAI**, please **do not open a public GitHub issue**.

Instead, email us at:

**security@prestoghana.com**  
(PGP public key: [link if available])

We will acknowledge receipt of your report within **48 hours** and aim to provide a resolution within **14 days**, depending on severity.

---

## 🛡 Supported Versions

We actively support and patch only the **latest major release** of LogAI.

| Version | Supported          |
| ------- | ------------------ |
| 0.x.x   | ✅ Yes              |
| < 0.x.x | ❌ No               |

---

## 🔐 Security Guidelines for Contributors

Because this project processes **application logs** that may contain sensitive data, please follow these rules when contributing:

1. **Never commit real production logs.**  
   Use anonymized or synthetic logs in tests and examples.

2. **Mask sensitive information.**  
   Before logs are sent to the AI model, they should be stripped or redacted of:
   - API keys
   - Passwords
   - Usernames & emails (unless synthetic)
   - IP addresses, unless anonymized

3. **Environment variables only.**  
   Store all tokens (Telegram, AI providers, Vector DB credentials) in `.env` files.  
   Never hardcode them in the source code.

4. **.gitignore sensitive files.**  
   Ensure `.env`, `.log`, `/data`, and other local files are excluded from git.

5. **Avoid exposing private errors publicly.**  
   If the bug report contains sensitive logs, share them privately with maintainers.

---

## 🧩 Responsible AI Use

- Be aware that logs sent to external AI providers (e.g., OpenAI, Anthropic) may leave your infrastructure.
- If compliance requires it, use **self-hosted models** with local vector stores.
- Encourage users to anonymize logs before enabling AI analysis.

---

## 🤝 Coordinated Disclosure

We believe in **coordinated vulnerability disclosure**.  
If you find an issue, work with us to fix it before making it public.  
We’ll give credit to all reporters in release notes (unless you prefer to remain anonymous).
