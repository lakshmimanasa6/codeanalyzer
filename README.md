# Code Analyzer Chatbot (LangGraph + Groq LLM)

An AI-powered **Code Analyzer Chatbot** built using **LangGraph, LangChain, Groq LLM, and Streamlit**.
The application allows users to paste a code snippet and receive **automated analysis, issue detection, and improvement suggestions** using an AI agent workflow.

---

# Features

* AI-powered **code analysis**
* Detects:

  * syntax issues
  * logical errors
  * performance problems
  * code quality issues
* Uses **LangGraph agent workflow**
* Interactive **Streamlit web interface**
* Uses **Groq Llama-3.1-8B model** for fast inference
* Maintains **conversation history**

---

# Tech Stack

Python

Streamlit – UI framework

LangChain – LLM framework

LangGraph – Agent workflow orchestration

Groq LLM – Fast inference

Llama-3.1-8B-Instant – Language model

---

# Project Architecture

User Input (Code Snippet)
↓
Prompt Creation Node
↓
LangGraph Agent
↓
LLM Analysis
↓
Response Generation
↓
Streamlit UI Display

---

# Project Structure

```
code_analyzer_project
│
├── code_analyzer.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Installation

## 1 Clone the repository

```
git clone https://github.com/yourusername/code-analyzer-ai.git
cd code-analyzer-ai
```

---

## 2 Create virtual environment

```
python -m venv genai_env
source genai_env/bin/activate
```

---

## 3 Install dependencies

```
pip install -r requirements.txt
```

If requirements file is missing install manually:

```
pip install streamlit langchain langchain-core langchain-community langchain-groq langgraph
```

---

# Setup API Key

Create an environment variable for your Groq API key.

Mac / Linux

```
export GROQ_API_KEY="your_api_key_here"
```

Windows

```
set GROQ_API_KEY=your_api_key_here
```

Never hardcode API keys inside code.

---

# Run the Application

```
streamlit run code_analyzer.py
```

or

```
python -m streamlit run code_analyzer.py
```

Streamlit will start a local server:

```
http://localhost:8501
```

---

# Example Usage

Paste code like:

```
for i in range(10)
    print(i)
```

The AI will analyze and respond with:

* syntax errors
* explanation
* improved version of code
* best practice suggestions

---

# Future Improvements

* Support multiple programming languages
* File upload support
* Static code analysis integration
* Code optimization suggestions
* GitHub repository analysis

---

# Author

Manasa Kommineni
AI & Machine Learning Student

---

# If you like this project

Give the repository a star on GitHub.
