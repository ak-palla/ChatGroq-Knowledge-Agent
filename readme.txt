ChatGroq Knowledge Agent

A conversational AI assistant built with **Streamlit**, **LangChain**, and **ChatGroq**, designed for real-time knowledge retrieval using **Wikipedia**, **Arxiv**, and **DuckDuckGo**. This app showcases a Retrieval-Augmented Generation (RAG) pipeline with a clean, interactive UI ideal for research and exploration.

---

 Features

- Conversational interface powered by ChatGroq
- Real-time web search with DuckDuckGo
- Scientific paper lookup via Arxiv API
- Encyclopedia-style search with Wikipedia API
- Agent-style responses with LangChain tools
- Streamlit UI for easy access and interaction

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ak-palla/chatgroq-knowledge-agent.git
cd chatgroq-knowledge-agent
```

### 2. Install Dependencies

Make sure you have Python 3.9+ installed. Then run:

```bash
pip install -r requirements.txt
```

> Note: You may need to install additional packages for LangChain and Streamlit integration if not already included.

### 3. Set Environment Variables

Create a `.env` file in the root directory and add your keys (e.g., Groq API key):

```
GROQ_API_KEY=your_api_key_here
```

### 4. Run the App

```bash
streamlit run test1.py
```

---

## Tech Stack

- Streamlit – Web UI framework
- LangChain – Framework for building LLM agents
- ChatGroq – Fast LLM backend for chat
- Wikipedia API
- Arxiv API
- DuckDuckGo Search

---

## File Structure

test1.py              # Main Streamlit app with agent logic  
.env                  # Environment variables (not committed)  
requirements.txt      # Python dependencies

---

