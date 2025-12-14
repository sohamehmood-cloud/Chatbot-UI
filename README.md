# Well-Being Chatbot

An interactive AI chatbot with both web and desktop UIs for mental well-being support.

## Features
- **Web UI (Flask)**: Modern browser-based interface at `http://127.0.0.1:5000`
- **Desktop UI (Tkinter)**: Standalone desktop application
- **Smart Responses**: Uses keyword matching to provide contextual support for stress, anxiety, sadness, tiredness, and motivation
- **Responsive Design**: Clean, modern interface with message history

## Files
- `main.py` — original console chatbot
- `chat_ui.py` — Tkinter desktop GUI
- `web_ui.py` — Flask web server
- `templates/index.html` — web UI template
- `static/chat.js` — client-side chat logic
- `static/style.css` — styling
- `wellbeing_library.json` — chatbot response library
- `requirements.txt` — Python dependencies

## Setup

### 1. Create Virtual Environment
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

### 2. Install Dependencies
```powershell
pip install -r requirements.txt
```

## Running

### Web UI (Browser)
```powershell
python web_ui.py
```
Then open http://127.0.0.1:5000 in your browser.

### Desktop UI (Tkinter)
```powershell
python chat_ui.py
```

### Console UI
```powershell
python main.py
```

## Customization
- **Styling**: Edit `static/style.css` to change colors, fonts, and layout
- **Responses**: Add new keywords and responses to `wellbeing_library.json`
- **Server Port**: Edit the `port=5000` parameter in `web_ui.py` to use a different port

## Technologies
- Python 3.7+
- Flask (web server)
- Tkinter (desktop GUI)
- JavaScript (frontend interactivity)

## Author
Created for mental well-being support and chatbot UI demonstration.
