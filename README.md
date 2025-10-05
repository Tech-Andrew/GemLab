# 💬 Gemini Playground

An interactive ***Tkinter-based AI chatbot GUI*** powered by ***Google Gemini*** (***google.generativeai***).  
It features multiple ***AI personas***, a ***light/dark theme switcher***, and real-time chat tools — all built in pure Python. ⚡

---

## 🌟 Features
- 🤖 ***Gemini Integration*** — Works with ***gemini-1.5*** and ***gemini-pro*** models.  
- 👤 ***Personas*** — Switch between ***Friendly***, ***Professional***, and ***Creative*** chat modes.  
- 🧠 ***Smart Model Picker*** — Automatically handles fallback and API recovery.  
- 🪟 ***Responsive GUI*** — Sleek 16:9 layout using Tkinter.  
- 🌗 ***Light/Dark Mode*** — Toggle themes on the fly.  
- 💾 ***Chat Tools*** — Summarize, export, or reset conversations.  
- 😄 ***Playful Touches*** — Emoji button, quick prompts, and dynamic footers.  

---

## 🧱 File Structure
```
main.py         # Main application file
```

---

## ⚙️ Requirements
- Python ***3.9+***
- Google Gemini API Key

Install dependencies:
```
pip install google-generativeai
```

---

## 🔑 Setup

### 1️⃣ Get your API key
Head to ***Google AI Studio*** → https://makersuite.google.com/app/apikey to create a Gemini API key.

### 2️⃣ Configure the key
Option A – Environment variable:
```
export GEMINI_API_KEY="your_api_key_here"
```

Option B – Inline key inside ***main.py*** (for quick testing only).

### 3️⃣ Run the app
```
python main.py
```

---

## 🎨 Interface Overview

| Section | Description |
|----------|-------------|
| 💬 ***Chat Window*** | Displays conversation history. |
| 🧠 ***Sidebar*** | Persona selector, tools, and quick prompts. |
| 🌈 ***Theme Toggle*** | Instantly switch between light/dark mode. |
| 📝 ***Input Box*** | Type your message and hit ***Enter*** or click ***Send***. |

---

## ⚡ Quick Prompts

| Example | Action |
|----------|--------|
| “Tell me a science fact” | Fun educational snippet |
| “Write a tiny story about space cats” | Creative storytelling |
| “Help me plan a productive day” | Structured advice |
| “Give me a brain teaser” | Interactive puzzles |

---

## 🧩 Tech Stack
- 🪄 ***google.generativeai*** — Gemini SDK  
- 🪟 ***Tkinter*** — GUI framework  
- ⚙️ ***Threading + Queues*** for async responses  
- 💬 ***ScrolledText*** widgets for chat display  
- 💾 ***Export/Summarize*** powered by Gemini itself  

---

## 🧠 App Logic
- Maintains conversation history for context  
- Persona-specific prompting system  
- Handles API errors gracefully  
- Real-time UI updates via ***after()*** loops  

---

## 🔮 Personas

| Persona | Description |
|----------|-------------|
| ***Friendly*** | Warm, conversational, emoji-rich |
| ***Professional*** | Clear, concise, and formal |
| ***Creative*** | Imaginative and story-driven |

---

## 🧰 Utilities

| Tool | Function |
|------|-----------|
| 🧾 ***Summarize Chat*** | Condenses your conversation |
| 💾 ***Export Chat*** | Saves chat to ***.txt*** or ***.md*** |
| 🧹 ***Clear Chat*** | Wipes the chat clean |
| 🌗 ***Toggle Theme*** | Switch between dark/light instantly |

---

## 🧑‍💻 Author
Built with ☕ + 💡 by ***[Your Name]***  
An open-source experiment blending ***AI***, ***design***, and ***Python wizardry***.

---

## 📜 License
***MIT License © 2025 [Your Name]***

---

> “Code is a conversation between you and the machine — make it sound good.” 💬✨
