# RAG-CREX-BOT 🏏

This is a simple project I built to learn **Retrieval-Augmented Generation (RAG)** using **LangChain**, **ChromaDB**, and **Cohere**.

It fetches IPL data from the **CREX website** (IPL 2020 and IPL 2023), splits the content, stores it in a vector database, and allows question-answering over the data using a retriever and Cohere LLM.

---

## 🔧 What I Used

- **LangChain** (for chaining and loading)
- **ChromaDB** (for vector storage)
- **Cohere** (for embeddings and LLM)
- **LangChainHub** prompt
- **Google Colab** for development

---

## 📌 Key Steps

1. Load IPL pages using `WebBaseLoader`
2. Split the text into chunks
3. Generate embeddings using Cohere
4. Store in ChromaDB
5. Build a simple RAG chain
6. Ask questions like:
   - "Who won IPL 2020?"
   - "What is the squad of Mumbai Indians in 2020?"
   - "Who won the final in IPL 2023?"

---

## ⚙️ Setup

Install dependencies:

```bash
pip install langchain_community langchainhub chromadb langchain langchain-cohere
```
