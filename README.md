# 🤖 Bidibo-AI

> Your intelligent personal AI assistant — offline-friendly, customizable, and built for real-life use cases.

Bidibo-AI is an open-source personal assistant that works **locally on your machine** with support for LLaMA, DeepSeek, or other cutting-edge models. Designed for flexibility, speed, and privacy, it can help with everything from checking your emails for OTPs to playing music and answering smart queries — all with your data in your control.

---

## 🌟 Features

- 🧠 **AI-Powered Tasks**  
  Use LLaMA, DeepSeek, or Grok-style local models for natural language understanding and generation.

- 📧 **Email Reader with OTP Detection**  
  Automatically checks your inbox and extracts OTPs or important updates.

- 📅 **Class Schedule Checker**  
  Fetch and display schedules from platforms like [online.udvash-unmesh.com](https://online.udvash-unmesh.com).

- 🎵 **YouTube Music Integration**  
  Play music from YouTube Music based on your commands.

- 🔍 **Web Search + Summarization (Optional)**  
  Ask real-world questions and get summarized results when online mode is enabled.

- 💾 **Memory and Personalization**  
  Learns and remembers your preferences, tasks, and data.

- 🛡️ **Privacy by Design**  
  Your data stays on your device unless you explicitly enable online services.

---

## 🧰 Tech Stack

- `Python 3.11+`
- `llama.cpp` / `Ollama` (for LLaMA/Grok/DeepSeek models)
- `SQLite` (for local memory)
- Shell scripting & Web APIs
- macOS Compatible (tested on MacBook Pro 2018)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/nabilbinbillal/Bidibo-AI.git
cd Bidibo-AI
