# RetailGPT : Semantic E-Commerce Chatbot 🤖🛒

An AI-powered chatbot for e-commerce platforms that enables real-time product recommendations and FAQ responses using semantic search and lightweight LLMs.

## 📌 Project Summary
This chatbot indexes and searches over 50K product descriptions to deliver relevant recommendations and automated answers to customer queries. Built for speed and scalability using MiniLM, TinyLlama, and FAISS with sentiment-aware filtering.

## ⚙️ Key Features
- **Semantic Search**: Uses FAISS + HNSW + PCA to efficiently search high-dimensional product embeddings.
- **LLM Response Generation**: Leverages TinyLlama for generating human-like responses.
- **Real-Time Performance**: Achieves <200ms response time for 50K+ items.
- **Sentiment-Aware Filtering**: Prioritizes results based on emotional tone of queries.
- **Modular Stack**: Built with clean, production-ready architecture (FastAPI, FAISS, Hugging Face).

## 🧠 Tech Stack
- **Language Models**: MiniLM, TinyLlama
- **Search**: FAISS (HNSW + PCA)
- **Backend**: Python, FastAPI
- **Optional Infra**: Pinecone, Redis
- **Tools**: Hugging Face Transformers, Scikit-learn, NumPy
