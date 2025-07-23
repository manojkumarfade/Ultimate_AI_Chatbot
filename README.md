# 🧠 Ultimate AI Chatbot

A versatile, feature-rich AI chatbot built with Streamlit, integrating multiple AI models (Gemini, Groq, OpenRouter, etc.), user authentication, chat history management, and various utilities like weather, news, code sandbox, resume builder, and more. The application features a modern, space-themed UI with glassmorphism effects, animations, and interactive tabs for different functionalities.

Live Demo: Frontend Website
(Note: This is a static landing page for the project. The full interactive experience requires running the Streamlit app locally or via a deployed backend.)

Utilities:
Weather updates (OpenWeatherMap API)
News headlines (Google News RSS)
Code sandbox with restricted execution
Resume builder (PDF generation)
Voice features (emotion detection, text-to-speech)
Language learning (conversation practice, grammar correction, vocabulary quizzes)
Social media post generator
Song recommendation by mood
Interactive games (Tic-Tac-Toe, Rock-Paper-Scissors, etc.)
Productivity tools (to-do list, reminders, study assistant)
Mental health tools (mood tracker, journal, meditation)
Health assistant (symptom analysis, health quiz)
Offline Mode: Caches data for limited functionality without internet.
Modern UI: Space-themed design with animations, glassmorphism, and a starfield background.

---

## 🚀 Features

User Authentication: Secure signup, login, and password reset with email OTP verification.
AI-Powered Chat: Integrates with multiple AI models (Gemini, Groq, OpenRouter, GitHub, A4F) with fallback mechanism.
Chat Modes: Custom personas (Friendly Tutor, Strict Coder, Motivational Coach, etc.) with auto-detection.

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

VIDEO FILE:

https://github.com/user-attachments/assets/e9257d15-a075-491b-9dd7-7a481ad9484c




<img width="1919" height="862" alt="Screenshot 2025-07-23 163858" src="https://github.com/user-attachments/assets/b5b88aad-624b-4f87-9cd7-4ab5aac4e6b3" />

<img width="1909" height="871" alt="Screenshot 2025-07-23 163919" src="https://github.com/user-attachments/assets/bd008bc6-89ec-4f35-8baa-8f8e8cdf1372" />

<img width="1911" height="872" alt="Screenshot 2025-07-23 163933" src="https://github.com/user-attachments/assets/f7c08918-43fe-49e8-aecf-21041bd89323" />

<img width="1916" height="871" alt="Screenshot 2025-07-23 163953" src="https://github.com/user-attachments/assets/c3a803dd-45b8-4fda-99b8-43fe1d115729" />

<img width="1919" height="866" alt="Screenshot 2025-07-23 164044" src="https://github.com/user-attachments/assets/b96ca490-f327-448c-86e3-cd302db27633" />

<img width="1917" height="874" alt="Screenshot 2025-07-23 164106" src="https://github.com/user-attachments/assets/c1a02ee2-3636-4f41-886f-d2304a5162c3" />

<img width="1571" height="833" alt="Screenshot 2025-07-23 165707" src="https://github.com/user-attachments/assets/39ef7dce-9a14-48c4-9f45-cf7c63fd2c9e" />

<img width="1919" height="833" alt="Screenshot 2025-07-23 173242" src="https://github.com/user-attachments/assets/4c6ef7b9-9e7b-443c-a6ef-0120000bd58f" />

<img width="1919" height="830" alt="Screenshot 2025-07-23 173253" src="https://github.com/user-attachments/assets/cafcd5bd-32ce-45ae-9454-2065bc6541a6" />

<img width="1916" height="865" alt="Screenshot 2025-07-23 173318" src="https://github.com/user-attachments/assets/a58b8d6a-a881-4b50-815f-e71fe0a666c1" />

<img width="1919" height="855" alt="Screenshot 2025-07-23 173329" src="https://github.com/user-attachments/assets/ad6425a8-645a-4f93-a532-e5d2e713b97c" />

<img width="1886" height="840" alt="Screenshot 2025-07-23 173343" src="https://github.com/user-attachments/assets/8610293a-692a-479b-90a9-fd3334a143b9" />

<img width="1919" height="869" alt="Screenshot 2025-07-23 173353" src="https://github.com/user-attachments/assets/c7b216ae-7551-4030-b7c1-7cf70e14e0ba" />

<img width="1918" height="896" alt="Screenshot 2025-07-23 173407" src="https://github.com/user-attachments/assets/6d41a38d-382c-410e-ba93-a52fafda5e51" />

<img width="1408" height="731" alt="Screenshot 2025-07-23 173425" src="https://github.com/user-attachments/assets/858fc32c-9e42-4827-9ee5-b40cb07677bf" />

<img width="1436" height="775" alt="Screenshot 2025-07-23 173504" src="https://github.com/user-attachments/assets/099761fb-3437-4aac-8510-821b510d3b82" />

<img width="1424" height="837" alt="Screenshot 2025-07-23 173515" src="https://github.com/user-attachments/assets/028aec8f-3242-4e0d-9968-1dc3ecb192b3" />

<img width="1434" height="846" alt="Screenshot 2025-07-23 174132" src="https://github.com/user-attachments/assets/039e343e-3e66-44f3-9fa2-a95ff4056185" />


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
