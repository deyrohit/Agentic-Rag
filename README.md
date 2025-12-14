# Agentic RAG System using LangGraph

An end-to-end **Agentic GenAI system** that combines Large Language Models with autonomous reasoning, tool usage, and Retrieval-Augmented Generation (RAG) to answer complex queries accurately and reliably.

---

## 🚀 Project Overview

This project implements an **autonomous Agentic RAG pipeline** using **LangGraph**, where an LLM acts as a planner and executor, dynamically deciding when to retrieve documents, validate information, and generate grounded responses.

Unlike traditional RAG systems, this solution supports **multi-step reasoning, memory, and tool invocation**, making it suitable for real-world knowledge-intensive applications.

---

## 🧠 Key Features

- ✅ Agentic architecture with **planner–executor workflow**
- ✅ Multi-step reasoning using **LangGraph**
- ✅ Retrieval-Augmented Generation (RAG)
- ✅ Tool calling for search, validation, and response synthesis
- ✅ Context-aware memory handling
- ✅ Modular, production-ready design

---

## 🛠️ Tech Stack

- **LLMs:** Qwen 
- **Agent Framework:** LangChain, LangGraph  
- **Retrieval:** FAISS 
- **Backend:** FastAPI  
- **Language:** Python  

---

## 🏗️ Architecture

1. **User Query**
2. **Planner Agent** decides the execution strategy
3. **Retriever Tool** fetches relevant documents from Vector DB
4. **Reasoning Agent** validates and synthesizes context
5. **Final Answer Generator** produces grounded output

---
