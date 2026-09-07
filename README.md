# ACUPUNCTURE-RAG-APP

An AI-powered Acupuncture Question Answering application built using Retrieval-Augmented Generation (RAG). The application retrieves relevant information from a knowledge base and uses an LLM to generate context-aware answers to user queries.

## 🚀 Project Overview

This project combines document retrieval and Large Language Models to create an intelligent chatbot focused on acupuncture-related information.

The system retrieves relevant content from the knowledge base using vector similarity search and provides it as context to the language model before generating the final response.

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- FAISS
- Hugging Face Embeddings
- Groq
- Llama LLM
- Jupyter Notebook

## 🔄 RAG Workflow

1. Load and prepare the knowledge base.
2. Split the information into smaller chunks.
3. Generate vector embeddings for the chunks.
4. Store embeddings in a FAISS vector database.
5. Convert the user's query into an embedding.
6. Retrieve the most relevant information from FAISS.
7. Pass the retrieved context to the LLM.
8. Generate and display the final answer through the Streamlit interface.

## ✨ Key Features

- Retrieval-Augmented Generation (RAG)
- Semantic search using vector embeddings
- FAISS-based similarity search
- LLM-powered question answering
- Interactive Streamlit interface
- Context-aware responses

## 📂 Project Structure

```text
ACUPUNCTURE-RAG-APP/
│
├── notebooks/
├── app.py
├── requirements.txt
└── README.md
