# Enterprise AI & Data Security Repository

This repository contains corporate-grade AI utilities optimized for scalable, resource-efficient local or cloud environments.

---

## 🚀 Project 1: Enterprise Retrieval-Augmented Generation (RAG) System
An interactive knowledge-base assistant that extracts semantic contexts from a vector database before utilizing a language model to answer queries.

### 🛡️ Core Highlights
* **Zero-Hallucination Guardrails:** Implements distance threshold checks to automatically separate internal corporate data lookups from general technical knowledge prompts.
* **Hardware-Safe Execution:** Optimized to execute entirely via cloud infrastructure using T4 instances, bypassing local machine hardware stress.

### 🛠️ Technology Stack
* **Vector Database:** ChromaDB (In-memory embedding storage)
* **Model Layer:** Qwen 2.5 Instruct via Hugging Face Transformers
* **Embedding Pipeline:** Sentence-Transformers (`all-MiniLM-L6-v2`)
* **Execution Framework:** PyTorch via CUDA Cloud Acceleration

### 💻 Live Cloud Execution
Click the badge below to open, execute, and interact with Project 1 inside Google Colab (Zero local installation required):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LOqiIj5eASEnOvAmDgKGbtCYbzjjEQOj)
