# FinTech Compliance Copilot

An **LLM-powered Retrieval-Augmented Generation (RAG) assistant** for navigating financial regulations.

This project ingests and indexes key regulatory texts — such as **PSD2**, **UK Payment Services Regulations 2017**, and **Money Laundering Regulations 2017** — and enables users to ask compliance-related questions with **grounded, source-cited answers**.

## 🎯 Objectives
- Provide **compliance officers** and **payments teams** with quick, accurate answers to regulatory questions.  
- Demonstrate how **LLM + RAG** can be applied in the **fintech and banking domain**.  
- Explore **retrieval evaluation** (Hit@k, MRR, groundedness).  

## ⚙️ Tech Stack
- **Python**  
- **Sentence Transformers / OpenAI embeddings**  
- **Qdrant / Elasticsearch** (vector + keyword retrieval)  
- **Streamlit / FastAPI** (interactive demo)  
- **Docker** (reproducibility)

---

🚧 *Work in progress — starting with PSD2 ingestion and indexing.*