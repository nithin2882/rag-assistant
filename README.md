# 🤖 RAG Assistant — Talk to Your Documents

## 🚀 Overview

This project implements a **Retrieval-Augmented Generation (RAG)** system that allows users to interact with their documents using natural language.

Users can upload documents and ask questions — the system retrieves relevant context and generates accurate answers using an LLM.

---

## 🧠 Architecture

1. Document Loading
2. Text Chunking
3. Embedding Generation
4. Vector Storage (FAISS)
5. Retrieval
6. LLM Response Generation

---

## 🛠️ Tech Stack

* Python
* LangChain
* OpenAI
* FAISS
* Streamlit

---

## ⚙️ How It Works

* Documents are split into chunks
* Each chunk is converted into embeddings
* Stored in a vector database
* User query → converted to embedding
* Top relevant chunks retrieved
* LLM generates final response

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## 💡 Key Features

* Semantic search over documents
* Context-aware responses
* Efficient retrieval using FAISS
* Modular pipeline design

---

## 📌 Future Improvements

* Add support for multiple file formats
* Improve chunking strategies
* Add conversation memory
* Deploy as API (FastAPI)

---

## 👨‍💻 Author

Nithin Rajan
