# Persistent Memory Agent System

An AI assistant that remembers conversations and research topics across sessions.

## Features

- Topic-specific memory persistence  
- Continues where you left off  
- Uses LLaMA2 locally via Ollama  
- Lightweight memory storage via TinyDB  
- Simple Streamlit frontend

## How to Run

1. Pull the model:  
   `ollama pull llama2`

2. Start Ollama:  
   `ollama run llama2`

3. Run app:  
   `streamlit run frontend.py`
