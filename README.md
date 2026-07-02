# Roast Master AI 🔥

> **Industrial-Strength Ego Destruction.** A full-stack, multi-agent AI orchestration pipeline that analyzes human profiles and dismantles your personality with surgical precision.

### 🚀 Live Demo
**[Experience the Burn Live Here](https://roast-master-frontend-gqv9.onrender.com)**

*(Onboarding includes a custom "Frustration Engine"—expect a couple of fake database connection timeouts before it lets you through!)*

---

## 🛠️ The Tech Stack

* **Frontend:** Vanilla JavaScript (ES6+), dynamic DOM sync via `localStorage`, and reactive dark-terminal UI built with Tailwind CSS. (Hosted on Render Static Sites).
* **Backend:** Asynchronous Python & Flask API, using `Flask-CORS` for secure cross-origin communication. (Hosted on Render Web Services via `gunicorn`).
* **AI Orchestration (`asyncio` + `liteLLM`):** Concurrent, fault-tolerant execution across three distinct AI providers running simultaneously:
  * **The Observer 😐:** Powered by **Groq** (`llama-3.3-70b-versatile`) — Extracts logical contradictions.
  * **The Sarcastic 🙄:** Powered by **Google Gemini** (`gemini-2.0-flash`) — Injects drippingly ironic retorts.
  * **The Brutal 💀:** Powered by **OpenRouter** (`meta-llama/llama-3.3-70b-instruct`) — Personal, high-hitting roasts.
  * **The Judge ⚖️:** Powered by **Groq** (`llama-3.3-70b-versatile`) — Sequential final layer that synthesizes all inputs into one devastating blow based on the session's **Heat Level**.

---

## ⚡ Key Highlights
* **True Parallel Processing:** Uses `asyncio.gather` so three distinct cloud providers compile context concurrently without bottlenecking the API response.
* **Decoupled Architecture:** Clean separation of UI and backend logic allows for quick scaling or swapping out core AI models seamlessly.
* **Zero-Trust Security:** Zero hardcoded keys in version control; fully containerized secrets deployment using cloud environment variables.
