# 🤖 AI Learning Repository

## Overview

Welcome to my AI Learning Repository!

This repository documents my journey of learning Artificial Intelligence through hands-on projects and experiments. Each notebook explores a core concept of Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), semantic search, and document-based question answering.

The projects are implemented using Python and Google Colab, helping me gain practical experience with modern AI technologies.

---

## 📂 Projects

### 📄 1. Chat with PDF

A simple AI application that allows users to ask questions about a PDF document. The notebook extracts text from the uploaded PDF and passes it as context to a Large Language Model (LLM) to generate answers.

**Concepts Covered**
- PDF text extraction
- Prompt engineering
- Context windows
- LLM-based question answering

---

### 🤖 2. Chatbot with Retrieval-Augmented Generation (RAG)

This project implements a Retrieval-Augmented Generation (RAG) pipeline. Instead of sending the entire document to the language model, it retrieves only the most relevant text using semantic search before generating a response.

**Concepts Covered**
- Document chunking
- Sentence embeddings
- FAISS vector database
- Semantic search
- Retrieval-Augmented Generation (RAG)

---

### 🚀 3. Chatbot with RAG (Version 2)

An enhanced version of the RAG chatbot that experiments with different chunking strategies and lightweight language models to improve retrieval and response generation.

**Concepts Covered**
- Advanced document chunking
- Embedding generation
- Semantic similarity search
- Lightweight LLMs
- End-to-end RAG workflow

---

### 📚 4. Context Window and Semantic Search

An educational notebook demonstrating how context windows, embeddings, and semantic search work together to improve document-based question answering.

**Concepts Covered**
- Context window limitations
- Document chunking
- Embeddings
- Vector databases
- Semantic search
- Similarity search

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Sentence Transformers
- FAISS
- PyPDF2
- Microsoft Phi-3 Mini
- TinyLlama

---
🔍 4. Hybrid Search Chatbot

This project extends the RAG pipeline by combining semantic search and keyword search to improve document retrieval. Semantic search retrieves information based on meaning using Sentence Transformers and FAISS, while keyword search retrieves information based on exact word matches using TF-IDF. The retrieved results are merged and provided as context to Phi-3 Mini, enabling more accurate and reliable answers.


**Concepts Covered**
Hybrid Search
Semantic Search
Keyword Search (TF-IDF)
Sentence Embeddings
FAISS Vector Database
Cosine Similarity
Document Chunking
Retrieval-Augmented Generation (RAG)
Prompt Engineering
Phi-3 Mini Integration

## 👩‍💻 Author

**Deepa Sivakumar**

