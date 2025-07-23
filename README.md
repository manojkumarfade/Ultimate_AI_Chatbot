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

<img width="1919" height="862" alt="Screenshot 2025-07-23 163858" src="https://github.com/user-attachments/assets/b5b88aad-624b-4f87-9cd7-4ab5aac4e6b3" />

<img width="1909" height="871" alt="Screenshot 2025-07-23 163919" src="https://github.com/user-attachments/assets/bd008bc6-89ec-4f35-8baa-8f8e8cdf1372" />

<img width="1911" height="872" alt="Screenshot 2025-07-23 163933" src="https://github.com/user-attachments/assets/f7c08918-43fe-49e8-aecf-21041bd89323" />

<img width="1916" height="871" alt="Screenshot 2025-07-23 163953" src="https://github.com/user-attachments/assets/c3a803dd-45b8-4fda-99b8-43fe1d115729" />

<img width="1919" height="866" alt="Screenshot 2025-07-23 164044" src="https://github.com/user-attachments/assets/b96ca490-f327-448c-86e3-cd302db27633" />

<img width="1917" height="874" alt="Screenshot 2025-07-23 164106" src="https://github.com/user-attachments/assets/c1a02ee2-3636-4f41-886f-d2304a5162c3" />

<img width="1571" height="833" alt="Screenshot 2025-07-23 165707" src="https://github.com/user-attachments/assets/39ef7dce-9a14-48c4-9f45-cf7c63fd2c9e" />



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
