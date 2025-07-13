# 🧠 Ultimate AI Chatbot

An all-in-one, multi-model AI assistant built with **Streamlit**.  
It supports everything from file Q&A, voice input, web search, resume review, image generation, daily tools, and even a health assistant tab — all in one clean interface.

---

## 🚀 Features

- 🔄 **Multi-model fallback**: OpenRouter, Groq, GitHub, A4F — switches automatically if one fails
- 🌐 **Web search integration** (Serper API)
- 🎤 **Voice-to-text & TTS** (speech recognition, gTTS, PyTTSx3)
- 🧾 **Document reader**: PDF, DOCX, TXT
- 🖼️ **Image generation & editing**
- 📄 **Smart resume reviewer & builder**
- 🪄 **PPT & PDF generator from prompt**
- 🧠 **Personality-based chat modes**: Tutor, Coder, Career Guide, etc.
- 📦 **Code sandbox** (secure Python exec with timeout)
- 🧪 **Health bot** (Ayurveda + modern suggestions)
- 🎮 **Game center** (trivia, riddles, emoji memory)
- 🎯 **Daily AI challenge**, analytics, themes, and more!

---

## 📦 Folder Structure

```bash
ultimate_ai_chatbot/
├── app.py               # Main Streamlit app
├── requirements.txt     # Dependencies
├── .gitignore           # Ignores secrets & cache
├── README.md            # You're reading it
├── saved_chats/         # Local chat history (excluded from GitHub)
└── secrets.toml         # Your API keys (DO NOT commit this)

💻 Local Run

git clone https://github.com/yourusername/ultimate_ai_chatbot.git
cd ultimate_ai_chatbot
pip install -r requirements.txt
streamlit run app.py
