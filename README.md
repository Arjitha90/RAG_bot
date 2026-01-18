# RAG_bot
A Retrieval-Augmented Generation (RAG) chatbot built with Streamlit, LangChain, ChromaDB, and LLMs to query PDF documents intelligently.

# File QA RAG Chatbot 

An end-to-end **Retrieval-Augmented Generation (RAG)** chatbot that allows users to upload PDF documents and ask natural language questions.

## Features
- PDF upload and parsing
- Chunking & vector embedding
- Semantic search using ChromaDB
- Context-aware answers using LLMs
- Source citation (page + document)
- Streamlit-based interactive UI

## Tech Stack
- Python
- Streamlit
- LangChain
- ChromaDB
- OpenAI / HuggingFace (pluggable)
- PyMuPDF

```md
```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🔐 API Key Setup

This project requires external API keys.  
For security reasons, API keys are NOT included in this repository.

### OpenAI API Key
1. Go to https://platform.openai.com/
2. Create an API key
3. Set it as an environment variable:

```bash
export OPENAI_API_KEY="your_key_here"
```

###Ngrok Auth Token

Go to https://dashboard.ngrok.com/get-started/your-authtoken

Copy your auth token
Set it as:

export NGROK_AUTH_TOKEN="your_token_here"

```python
import os

OPENAI_API_KEY = os.getenv("OPENAI_API_KEY")
NGROK_AUTH_TOKEN = os.getenv("NGROK_AUTH_TOKEN")
```



