# networking-chatbot
# 🌐 AI-Powered Network Troubleshooting Chatbot

An AI-powered Network Troubleshooting Assistant that leverages **Retrieval-Augmented Generation (RAG)** to provide accurate, context-aware solutions for Cisco networking issues. The application combines a React frontend, FastAPI backend, ChromaDB vector database, HuggingFace embeddings, and the Llama 3.2 Large Language Model through Ollama to answer networking queries using Cisco documentation.

---

## 🚀 Features

- 🤖 AI-powered conversational chatbot
- 📚 Retrieval-Augmented Generation (RAG)
- 🔍 Semantic search using vector embeddings
- 📖 Answers grounded in Cisco documentation
- ⚡ FastAPI REST API backend
- 🎨 Interactive React frontend
- 📝 Markdown response rendering
- 🧠 Llama 3.2 integration via Ollama
- 📂 ChromaDB vector database
- 🔗 LangChain-powered retrieval pipeline
- 💬 Context-aware troubleshooting assistance
- 🌐 Full-stack architecture

---

## 🏗️ Architecture

```
                User
                  │
                  ▼
          React Frontend
                  │
          REST API (FastAPI)
                  │
        Network Query
                  │
                  ▼
        LangChain RAG Pipeline
          │               │
          ▼               ▼
    ChromaDB         Ollama
(Vector Search)    (Llama 3.2)
          │               │
          └──────► Response
                  │
                  ▼
          React Chat Interface
```

---

## 🛠 Tech Stack

### Frontend
- React
- Vite
- Axios
- React Markdown
- CSS

### Backend
- FastAPI
- Python
- LangChain
- Ollama
- Llama 3.2
- ChromaDB
- HuggingFace Embeddings
- Pydantic

### AI & Machine Learning
- Retrieval-Augmented Generation (RAG)
- Semantic Search
- Vector Embeddings
- Prompt Engineering
- Large Language Models (LLMs)

---

## 📂 Project Structure

```
chatbot/
│
├── backend/
│   ├── main.py
│   ├── rag_pipeline.py
│   └── prompts.py
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── chroma_db/
├── knowledge_base/
├── ingest.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/network-troubleshooting-chatbot.git

cd network-troubleshooting-chatbot
```

---

### Install Python Dependencies

```bash
pip install -r requirements.txt
```

---

### Install Frontend Dependencies

```bash
cd frontend

npm install
```

---

## 🧠 Install Ollama

Download Ollama:

https://ollama.com/download

Pull the Llama 3.2 model:

```bash
ollama pull llama3.2
```

Start Ollama:

```bash
ollama serve
```

---

## ▶ Running the Backend

```bash
uvicorn backend.main:app --reload
```

Backend runs at

```
http://127.0.0.1:8000
```

---

## ▶ Running the Frontend

```bash
cd frontend

npm run dev
```

Frontend runs at

```
http://localhost:5173
```

---

## 📚 Knowledge Base

The chatbot retrieves information from:

- Cisco Configuration Guides
- Cisco Troubleshooting Documentation
- RFC Documents
- Custom Networking Q&A Dataset

These documents are embedded using HuggingFace sentence transformers and stored in ChromaDB for semantic retrieval.

---

## 💬 Example Questions

- What is OSPF?
- Configure VLAN 10 on a Cisco switch.
- Why can't I ping another subnet?
- Explain the Spanning Tree Protocol.
- Troubleshoot DHCP issues.
- What is the difference between RIP and OSPF?
- Configure NAT on a Cisco router.
- How do ACLs work?

---

## 🎯 Key Features Implemented

✔ Retrieval-Augmented Generation (RAG)

✔ Semantic Document Search

✔ Cisco Knowledge Base

✔ Prompt Engineering

✔ Vector Database

✔ FastAPI REST APIs

✔ React Chat Interface

✔ Markdown Rendering

✔ LLM Integration using Ollama

✔ Context-Aware Responses

✔ Full-Stack AI Application

---

## 📈 Future Enhancements

- Streaming AI responses
- Conversation memory
- Chat history
- User authentication
- File upload support
- Voice input
- Dark/Light theme
- Response citations
- Docker deployment
- Cloud deployment

---


## 👩‍💻 Author

**Nidhii Mallavarapu**

Electronics & Telematics Engineering

Minor in Artificial Intelligence & Machine Learning

GitHub: https://github.com/nidhii2024

LinkedIn: https://linkedin.com/in/nidhii m

---

## ⭐ If you found this project useful, consider giving it a star!
