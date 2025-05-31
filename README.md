# Virtual-Assistant

# 🤖 Voice-Enabled Virtual Assistant with AI & News Integration

A Python-based **Virtual Assistant** that listens to your voice or accepts text input, then performs a range of tasks like opening YouTube, reading news, checking system updates (simulated), and even generating AI images using OpenAI’s DALL·E.

---

## 🧠 Features

- 🎙️ Voice and Text Input Modes
- 📺 Open YouTube via voice command
- 📰 Fetches top news headlines (via News API)
- ⚙️ Simulated system update checker
- 🧠 AI-powered image generation using OpenAI's DALL·E
- 🔊 Text-to-speech response using `pyttsx3`

---

## 🛠️ Technologies Used

- **Python 3**
- `speech_recognition` – for recognizing spoken commands
- `pyttsx3` – for converting text to speech
- `webbrowser` – to open web pages
- `requests` & `json` – to fetch and process API responses
- `openai` – to generate images using DALL·E
- `NewsAPI` – to get real-time news headlines

---

## 🚀 Getting Started

### 📦 Installation

1. Clone the repository or copy the code into a Python file (e.g., `assistant.py`)
2. Create a virtual environment (optional but recommended)
3. Install required packages:

```bash
pip install -r requirements.txt
