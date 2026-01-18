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

```bash
pip install -r requirements.txt
streamlit run app.py
