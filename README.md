# AI Study Hub

A modern academic learning app built with:
- Flask backend
- JSON file storage
- Tailwind CSS + vanilla JS frontend
- AI notes generator
- academic chatbot
- forgot password with email reset
- DOCX and PDF export

## Folder Structure
```

## Gemini API setup

Add your Gemini API key to the root `.env` file:

```text
GEMINI_API_KEY=your-gemini-api-key
GEMINI_MODEL=gemini-2.5-flash
```

Install backend dependencies with `python -m pip install -r backend/requirements.txt`, then start the app with `python backend/app.py`. Both AI notes and academic chat use Gemini. Keep `.env` private and never commit API keys.text
project/
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── data/
│       ├── subjects.json
│       ├── users.json
│       ├── chat_sessions.json
│       ├── chat_messages.json
│       └── password_reset_tokens.json
├── frontend/
│   ├── index.html
│   ├── dashboard.html
│   ├── generate.html
│   ├── note.html
│   ├── reset.html
│   ├── css/
│   │   └── style.css
│   └── js/
│       ├── api.js
│       └── layout.js
├── .env
├── README.md
└── run.sh