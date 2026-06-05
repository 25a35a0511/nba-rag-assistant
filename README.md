# 📘 NBA Accreditation AI Assistant (RAG-based)

---

## 🤖 Overview

This project is a **Retrieval-Augmented Generation (RAG)-based AI assistant** designed to help faculty with **NBA accreditation processes**.

It allows users to upload and query academic documents such as:
- Self Assessment Reports (SAR)
- NBA accreditation criteria documents
- CO–PO mapping files
- Institutional academic records

The system retrieves relevant information from documents and generates **context-aware, accurate responses**, reducing manual effort and improving accreditation efficiency.

---

## 🎯 Key Features

- 📄 Upload and query NBA-related PDF documents  
- 🤖 AI-powered chatbot for accreditation assistance  
- 📝 Supports **Self Assessment Report (SAR)** preparation  
- 🔗 CO–PO (Course Outcome – Program Outcome) mapping support  
- 🔍 Context-aware document retrieval using RAG  
- ⚡ Fast semantic search using vector embeddings  
- 🧠 Reduces manual workload in accreditation tasks  
- 📚 Domain-specific responses based on uploaded documents  

---

## ⚙️ How It Works

The system follows a **Retrieval-Augmented Generation (RAG)** pipeline:

1. **Document Loading**
   - NBA manuals, SAR reports, and academic PDFs are loaded  

2. **Text Splitting**
   - Documents are split into smaller chunks  

3. **Vector Embedding**
   - Text chunks are converted into embeddings  

4. **Vector Storage**
   - Embeddings are stored in FAISS vector database  

5. **Retrieval**
   - User query fetches relevant document sections  

6. **Generation**
   - AI model generates responses using retrieved context  

---

## 🧱 Tech Stack

- 🧠 LangChain – LLM orchestration framework  
- 🔍 FAISS – Vector similarity search  
- 🤖 LLM (IBM Granite / OpenAI) – Response generation  
- 📊 Streamlit – User interface  
- 🔗 RAG Architecture – Retrieval + Generation system  

---

## 🏛️ Domain Use Case

This project is designed for **academic accreditation support systems**, including:

- NBA Accreditation assistance  
- Self Assessment Report (SAR) preparation  
- CO–PO mapping guidance  
- Academic documentation search  
- Faculty productivity enhancement  

---

## 🚀 Running the Project

```bash
streamlit run app.py
```
## 📄 License

This project is licensed under the **Apache License 2.0**.  
You are free to use, modify, and distribute this project with proper attribution.

---

## ⭐ Conclusion

This project demonstrates how **Artificial Intelligence and Retrieval-Augmented Generation (RAG)** can be effectively used to simplify NBA accreditation tasks, improve documentation accuracy, and assist faculty in academic processes.
