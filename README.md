# 🤖 AI Learning Repository

## Overview

Welcome to my AI Learning Repository!

This repository documents my journey of learning Artificial Intelligence through hands-on projects and experiments. Each notebook explores fundamental concepts of Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), semantic search, document processing, and AI-powered question answering.

All projects are implemented using **Python** and **Google Colab**, helping me gain practical experience with modern AI technologies and build a strong foundation in Generative AI.

---

# 📂 Projects

## 📄 1. Chat with PDF

A simple AI application that allows users to ask questions about a PDF document. The notebook extracts text from an uploaded PDF and passes it as context to a Large Language Model (LLM) to generate answers.

### Concepts Covered

- PDF text extraction
- Prompt engineering
- Context windows
- LLM-based question answering

---

## 🤖 2. Chatbot with Retrieval-Augmented Generation (RAG)

This project implements a Retrieval-Augmented Generation (RAG) pipeline. Instead of sending the entire document to the language model, it retrieves only the most relevant chunks using semantic search before generating a response.

### Concepts Covered

- Document chunking
- Sentence embeddings
- FAISS vector database
- Semantic search
- Retrieval-Augmented Generation (RAG)

---

## 🚀 3. Chatbot with RAG (Version 2)

An enhanced version of the RAG chatbot that experiments with different chunking strategies and lightweight language models to improve retrieval quality and response generation.

### Concepts Covered

- Advanced document chunking
- Embedding generation
- Semantic similarity search
- Lightweight LLMs
- End-to-end RAG workflow

---

## 📚 4. Context Window and Semantic Search

An educational notebook demonstrating how context windows, embeddings, and semantic search work together to improve document-based question answering.

### Concepts Covered

- Context window limitations
- Document chunking
- Embeddings
- Vector databases
- Semantic search
- Similarity search

---

## 🔍 5. Hybrid Search Chatbot

This project extends the RAG pipeline by combining **semantic search** and **keyword search** to improve document retrieval.

Semantic search retrieves information based on meaning using **Sentence Transformers** and **FAISS**, while keyword search retrieves exact word matches using **TF-IDF**. The retrieved results are merged and passed to **Phi-3 Mini** to generate more accurate responses.

### Concepts Covered

- Hybrid Search
- Semantic Search
- Keyword Search (TF-IDF)
- Sentence Embeddings
- FAISS Vector Database
- Cosine Similarity
- Document Chunking
- Retrieval-Augmented Generation (RAG)
- Prompt Engineering
- Phi-3 Mini Integration

---

## 🎯 6. Hybrid Search with Cross-Encoder Re-ranking

This project enhances Hybrid Search by introducing a **Cross-Encoder** as a re-ranking model.

After retrieving candidate chunks using semantic search (FAISS) and keyword search (TF-IDF), the results are merged and duplicate chunks are removed. A Cross-Encoder (`cross-encoder/ms-marco-MiniLM-L-6-v2`) then scores each candidate chunk based on the user query. Only the highest-ranked chunks are sent to the Large Language Model, improving retrieval accuracy and answer quality.

### Workflow

```
PDF
 │
 ▼
Chunking
 │
 ▼
Embeddings
 │
 ▼
FAISS Semantic Search
 │
 ├──────────────┐
 │              │
 ▼              ▼
Top Semantic    Keyword Search
Chunks          (TF-IDF)
 │              │
 └──────┬───────┘
        ▼
 Merge Results
        ▼
 Remove Duplicates
        ▼
 Cross-Encoder Re-ranking
        ▼
 Top Relevant Chunks
        ▼
 Phi-3 Mini
        ▼
 Final Answer
```

### Concepts Covered

- Hybrid Search
- Semantic Search
- Keyword Search (TF-IDF)
- Cross-Encoder Re-ranking
- Sentence Transformers
- FAISS
- Cosine Similarity
- Candidate Retrieval
- Retrieval-Augmented Generation (RAG)
- Prompt Engineering

---

## ✂️ 7. Smart Document Chunking using LangChain

This project demonstrates how to split PDF documents into meaningful chunks using LangChain's **RecursiveCharacterTextSplitter**.

Unlike fixed-size chunking, RecursiveCharacterTextSplitter preserves the natural structure of a document by recursively splitting text using paragraphs, new lines, sentences, words, and finally characters when necessary. This produces higher-quality chunks for Retrieval-Augmented Generation (RAG) systems.

### Concepts Covered

- LangChain Text Splitters
- RecursiveCharacterTextSplitter
- Smart Document Chunking
- Chunk Size
- Chunk Overlap
- Document Preprocessing
- PDF Text Extraction
- Preparing Documents for RAG

---

# 🛠️ Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Sentence Transformers
- LangChain
- FAISS
- Scikit-learn (TF-IDF)
- PyPDF
- Microsoft Phi-3 Mini
- TinyLlama

---

# 👩‍💻 Author

**Deepa Sivakumar**

Python Developer | AI Engineer (Learning) | Building hands-on Generative AI projects
