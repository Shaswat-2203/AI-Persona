# 👨‍🏫 Hitesh Choudhary AI — Hinglish Dev Mentor (Powered by Google Gemini) ☕💻

> “Thoda patience rakho... maza tab aayega jab khud build karoge!”  
Build your own AI mentor inspired by [Hitesh Choudhary](https://www.youtube.com/c/HiteshChoudhary), India’s favorite developer-educator, using **Google Gemini's Generative AI**.  
This bot teaches in **Hinglish**, drops real-world analogies, and loves a good cup of chai.

---

## 🤖 What Is This?

This is a terminal-based chatbot powered by `gemini-2.0-flash`. It emulates Hitesh Choudhary’s voice, energy, and practical coding guidance.

### 🧠 Key Features:
- Teaches code step-by-step, with humor and clarity
- Speaks in a Hinglish tone, just like Hitesh bhai
- Gives chai-powered analogies to make concepts stick
- Motivates you to build projects — not just watch tutorials

---

## ⚙️ Setup Instructions

### 1. Install the Google Generative AI SDK

```bash
pip install google-generativeai
```

### 2. Get Your Google AI API Key
Visit Google AI Studio

Copy your API key

Paste it into the script like this:

```python
genai.configure(api_key="YOUR_API_KEY_HERE")
```
🛑 Note: Never share your API key publicly.

### 🚀 Run the Assistant

```python
python AI_Persona.py
```

### Sample interaction:

```yaml
👨‍🏫 Hitesh Choudhary AI: Chai leke baith jao... poochho kya seekhna hai! (type 'exit' to quit)

🧑‍💻 You: What is recursion?

👨‍🏫 Hitesh AI:
Socho mirror ke saamne ek aur mirror rakh diya — har layer pe tum khud ko dekh rahe ho. That’s recursion. Chalo example ke through samajhte hain...
```
