﻿# AI-Agents-with-langchain

🌐 Multi-Agent Web Search with Langchain
A powerful and extensible framework built using Langchain to demonstrate multi-agent collaboration for performing intelligent web searches. This project showcases how multiple agents can interact, share context, and dynamically reason to fulfill a task efficiently.

🚀 Features
🔍 Multi-agent orchestration with Langchain

🧠 Intelligent query parsing and task delegation

📚 Notebook (agents_demo.ipynb) for interactive experimentation

💡 Environment-configurable for various APIs and tools

🛠️ Lightweight Flask app (app.py) to serve the logic

📁 Project Structure
bash
Copy
Edit
AI-Agents-with-Langchain/
│
├── app.py                 # Flask app for agent interaction
├── agents_demo.ipynb      # Jupyter Notebook demo
├── requirements.txt       # Dependencies
├── .env                   # Environment variables (e.g., API keys)
├── examples.db            # Example database
├── example.txt            # Sample input/output text
└── example_new.db         # Additional DB for demos
🧰 Requirements
Install dependencies with:

bash
Copy
Edit
pip install -r requirements.txt
⚙️ Setup
Clone the repo

⚙️ Setup
Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/multiagent_web_search.git
cd multiagent_web_search/AI-Agents-with-Langchain
Set up your .env file

env
Copy
Edit
OPENAI_API_KEY=your_openai_key
SERPAPI_API_KEY=your_serpapi_key
Run the Flask App

bash
Copy
Edit
python app.py
📓 Notebook Demo
Explore the agents_demo.ipynb to see how multi-agent tasks can be triggered and managed interactively.

🔒 Notes
Don't forget to add .env and .db files to .gitignore if publishing.

Make sure you have valid API keys for OpenAI and SerpAPI if applicable.

📜 License
MIT License. See LICENSE for details.

