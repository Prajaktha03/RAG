# RAG
A step-by-step guide and implementation project demonstrating how to build a Retrieval-Augmented Generation (RAG) pipeline to query custom documents using Large Language Models (LLMs).

## 📌 Features
Document Loading: Parse PDF, TXT, or Markdown files.
Text Chunking: Split text into manageable chunks using recursive character splitting.
Embedding Generation: Convert text chunks into vector embeddings.
Vector Store Integration: Index and retrieve context using a vector database (e.g., ChromaDB / FAISS).
LLM Generation: Pass retrieved context alongside user queries to generate grounded responses.
