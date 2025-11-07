# 🔎 Hybrid Semantic Search Engine

This project is a **hybrid search engine** that combines:
- **BM25 (sparse retrieval)** using Pyserini/Lucene
- **Dense retrieval** using FAISS + SentenceTransformers
- A **Streamlit UI** for interactive search

It allows you to query a dataset (e.g., MS MARCO subset) and see results ranked by a fusion of BM25 and semantic similarity.

---

## 📂 Project Structure
