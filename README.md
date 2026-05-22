# AI-Powered Personal Finance Tracker

## Description

This project is an AI-powered personal finance assistant built using Python, OpenAI API, Gradio, and SQLite.

The application allows users to track income and expenses using natural language.

Example inputs:
- "My salary is 3000 for May 2026"
- "I spent 50 on lunch"

The AI understands user messages, calls the correct tools/functions, and stores the data in a SQLite database.

---

# Technologies Used

- Python
- OpenAI API
- Gradio
- SQLite
- Function Calling / Tool Calling
- dotenv

---

# Setup Instructions

## 1. Clone the repository

```bash
git clone <your-github-repository-link>
cd AI-Personal-Finance-Tracker
```

## 2. Activate virtual environment

```bash

```

## 3. Install dependencies

```bash
uv add -r requirements.txt
```

---

# Add OpenAI API Key

Create a `.env` file in the project root and add:

```env
OPENAI_API_KEY=your_api_key_here
```

---

# How to Run

1. Open the notebook:

```text
financetracker.ipynb
```

2. Run all cells

3. The Gradio UI will launch automatically
.venv\Scripts\activate
---

# Features

- Add salary using natural language
- Log expenses
- View remaining balance
- Get expense summary by category
- AI-powered conversational interface

---


# Learning Outcomes

This project helped me learn:
- OpenAI API integration
- AI function/tool calling
- Prompt engineering basics
- Building AI-powered applications
- Gradio UI development
- SQLite database integration