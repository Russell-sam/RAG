# 📖 Retrieval-Augmented Generation (RAG) – Constitution of Kenya Project

## 📌 Project Overview
This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using the **Constitution of Kenya (2010)** as the knowledge base.  
The system allows users to ask natural language questions (e.g., *“What does the Constitution say about the right to life?”*) and receive grounded answers from the official document.  

---

## ⚙️ Features
- **PDF Loader** → Extracts text from the Constitution.  
- **Text Chunking** → Splits text into manageable chunks for retrieval.  
- **Embeddings** → Creates semantic vector representations using HuggingFace (`MiniLM`).  
- **Vector Database** → Stores chunks in **FAISS** for fast similarity search.  
- **Groq LLM** → Uses Groq’s Llama 3 models for generating accurate answers.  
- **RAG Pipeline** → Combines document retrieval with LLM reasoning.  

---
