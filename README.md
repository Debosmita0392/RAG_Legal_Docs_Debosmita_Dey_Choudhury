# RAG_Legal_Docs_Debosmita_Dey_Choudhury

This repository contains the final solution for the RAG-based Legal QA task.

## 📘 Contents

- `RAG_Legal_Solved.ipynb` – Complete notebook with:
  - Preprocessing
  - Chunking
  - FAISS-based vector DB creation
  - HuggingFace RAG pipeline
  - BLEU, ROUGE, RAGAS evaluations
- All steps can be executed locally

## 💡 Notes

- Uses `sentence-transformers/all-MiniLM-L6-v2` for embeddings
- RAG evaluation includes both local and OpenAI-based pipelines
- Set `OPENAI_API_KEY` for RAGAS evaluation
