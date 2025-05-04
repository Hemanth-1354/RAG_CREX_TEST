# RAG-CREX-BOT 🏏

This is a simple test project I built to learn **Retrieval-Augmented Generation (RAG)**, **LangChain**, **ChromaDB**, and **Cohere**.

It fetches IPL data from the **CREX website** (IPL 2020 and IPL 2023), splits the content, stores it in a vector database, and allows question-answering over the data using a retriever and Cohere LLM.

---

##  What I Used

- **LangChain** (for chaining and loading)
- **ChromaDB** (for vector storage)
- **Cohere** (for embeddings and LLM)
- **rlm/rag-prompt-mistral (LangChainHub)** prompt  (Mistral model format, but works with Cohere too)
