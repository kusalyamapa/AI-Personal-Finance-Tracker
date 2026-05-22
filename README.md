# AI-powered personal finance tracker
##Description
This project is an AI-powered personal finance assistant that helps users track their income and expenses using natural language.

Users can simply type messages like:
- "My salary is 3000 for May 2026"
- "I spent 50 on lunch"

The AI understands the input, calls the correct tools, and stores data in a SQLite database.

## Setup Instructions
1.install dependencies

.venv\Scripts\activate - activate virtual environment
uv add -r requirements.txt

2.Add openai API key:
create a '.env' file and add inside that file 
OPENAI_API_KEY = my_api_key_here

# How to run
1.Open the notebook:
  financetracker.ipynb

2.Run all cells

3.The gradio UI will launch automatically

# Features
1.Add salary using natural language
2.Log expenses
3.View remaining balance
4.Get expense summary by category

# Screenshort
![Set salary test](Screenshots/Image1.png)
![Log expense test](Screenshots/Image2.png)
![Balance check](Screenshots/Image3.png)
![Summary report](Screenshots/Image4.png)