# RAG Chatbot with Ollama gemma:2b

This project implements a Retrieval-Augmented Generation (RAG) chatbot using LangChain and the lightweight Ollama `gemma:2b` model. The system can ingest text files, PDFs, and web pages, process them into embeddings, store them in a vector database, and answer user queries using similarity search.

## Features

- Load and process documents from:
  - Text files (`.txt`)
  - PDF files (`.pdf`)
  - Web pages (HTML content)
- Split large documents into manageable chunks for embedding
- Generate vector embeddings using Ollama `gemma:2b`
- Store and search embeddings using FAISS or Chroma
- Retrieve answers to user queries using semantic similarity
- Optional Streamlit interface for interactive querying

## Project Structure

- `RAGPipeline.ipynb` – Jupyter Notebook demonstrating data ingestion, document splitting, embedding, vector storage, and querying
- `speech.txt` – Speech Text file for Information Retrieval.
- `attention.pdf` - A research paper for information retrieval.
- `requirements.txt` – Python dependencies

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/RAGChatbot.git
cd RAGChatbot
```

```bash
python -m venv venv
```

```bash
pip install -r requirements.txt
```

```bash
ollama pull gemma:2b
```


