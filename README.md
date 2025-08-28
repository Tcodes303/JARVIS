# J.A.R.V.I.S. - Gemini Voice Interface

J.A.R.V.I.S. is a cross-platform desktop voice assistant powered by the Gemini AI model. It supports text and speech input, real-time responses, typing animation, and offline text-to-speech.

---

## Features

- Voice input (speech recognition)
- Text input with chat history
- Typing animation for AI responses
- Offline TTS using `pyttsx3`
- Gemini AI integration (requires API key)
- Fully English interface
- Cross-platform: Windows, Linux, macOS

---

## Installation & Start
Download the correct .zip for your OS and extract it. 
### Windows
```bash
cd JARVIS_WIN
pip install -r requirements.txt
python jarvis_win.py
```
### MacOS
```bash
brew install portaudio
cd JARVIS_MAC
pip install -r requirements.txt
python jarvis_mac.py
```

### Linux
```bash
sudo apt install portaudio19-dev
cd JARVIS_LINUX
pip install -r requirements.txt
python jarvis_linux.py
```

### General

To use the AI please go to [Google AI](https://ai.google.dev/gemini-api/docs?hl) and get yourself a api key for gemini-2.0-flash that you need to paste at
```bash
API_KEY = "YOUR_API_KEY_HERE"
```
