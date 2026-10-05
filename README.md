# TruthRAG: Enterprise AI Research Assistant

## Overview

TruthRAG is a Retrieval-Augmented Generation (RAG) system that answers questions from PDF documents using semantic search and large language models.

## Features

- PDF Ingestion
- Document Chunking
- Semantic Search
- ChromaDB Vector Database
- Groq LLM Integration
- Citation Generation
- Hallucination Detection

## Tech Stack

- Python
- ChromaDB
- LangChain
- Sentence Transformers
- Groq API
- GPT-OSS-20B
- NLP
- Information Retrieval

## Architecture

User Query
↓
Retriever
↓
ChromaDB
↓
Relevant Context
↓
Groq LLM
↓
Answer Generation
↓
Citations
↓
Hallucination Verification

## Project Status

✅ MVP Completed

### Future Improvements

- RAGAS Evaluation
- Streamlit UI
- FastAPI Deployment
