# 🚀 GovSchemesHub

A backend-powered project that helps users **retrieve government schemes efficiently** using **RAG (Retrieval-Augmented Generation)** and vector databases.

---

## 📌 Features

- 🔍 Intelligent scheme search using semantic retrieval  
- 🤖 LLM-powered responses  
- 📄 Dataset-based knowledge system  
- ⚡ Fast retrieval using vector database (ChromaDB)  
- 🧠 Modular backend architecture  

---

## 🏗️ Project Structure

GovSchemesHub/
│
├── Backend/
│ ├── Gov/
│ │ ├── main.py
│ │ ├── retriever.py
│ │ ├── vectorDB.py
│ │ ├── llm_chain.py
│ │ ├── document_loader.py
│ │ └── chunks.py
│ │
│ ├── docs/
│ │ └── agriculture_schemes_dataset.txt
│ │
│ ├── chroma_db/ # (ignored in Git)
│ ├── pycache/ # (ignored in Git)
│ └── .env # (ignored in Git)


---

## ⚙️ Tech Stack

- 🐍 Python  
- 🧠 LangChain (RAG pipeline)  
- 🗄️ ChromaDB (Vector Database)  
- 🤖 LLM Integration  
- 📂 Custom dataset  

---

## 🔐 Environment Variables

Create a `.env` file in the Backend folder:

```env