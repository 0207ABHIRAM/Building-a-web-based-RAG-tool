# Web-Based RAG Tool

This project is a Retrieval-Augmented Generation tool that lets you query a product catalog stored in a GitHub repository.

## Features
- GitHub integration to fetch product catalog
- Semantic search using FAISS
- Embedding via Sentence Transformers
- Simple FastAPI backend and React frontend

## Setup

### Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn app:app --reload
