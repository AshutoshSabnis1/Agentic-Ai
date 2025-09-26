# Gemini with OpenAI-Compatible API (via Cursor)

This project shows how to use **Google Gemini** through its **OpenAI-compatible API** inside Cursor.  
It demonstrates loading API keys from `.env`, setting up the Gemini client, and running a chat completion workflow.

---

## 🚀 Features
- Secure API key handling with `.env`
- Uses the `OpenAI` client but points it at Gemini’s API endpoint
- Runs a simple math test (`2+2`) to verify setup
- Generates a **challenging IQ-style question** and then answers it
- Outputs results in both plain text and formatted Markdown (Jupyter friendly)

---

## 📂 Project Structure

─ main.py # Main Python script (Gemini example)
─ .env # Environment variables file (not to be committed)
─ README.md # Project documentation

## 🔑 Setup

1. **Open in Cursor**  
   Clone or create this project in Cursor (or VS Code if preferred).

2. **Create a `.env` file** in the root directory with your Gemini API keys:
   ```ini
   GEMINI_API_KEY=your_gemini_key_here
   GOOGLE_API_KEY=your_google_key_here

Install dependencies:
pip install python-dotenv openai ipython
