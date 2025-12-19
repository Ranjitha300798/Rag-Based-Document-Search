# Rag-Based-Document-Search
Built an LLM-powered semantic document search and summarization system that retrieves relevant information from large text corpora and generates concise, coherent summaries using transformer-based language models.

DATA PIPELINE:
Wikipedia Corpus → Text Cleaning & Chunking → Sentence Embeddings Generation → FAISS Vector Indexing → Semantic Search → LLM-based Summarization → Streamlit Web Deployment

FEATURES:

Semantic document search using Sentence Transformers + FAISS

Hybrid retrieval returning Top-K relevant document chunks

Abstractive summarization using BART (facebook/bart-large-cnn)

Safe multi-chunk summarization to handle long documents

User-controlled parameters: number of results & summary length

Interactive Streamlit-based web interface

Evaluation using Precision@K and ROUGE (ROUGE-1, ROUGE-L) metrics

TECH STACK:
Python | Sentence Transformers | FAISS | Hugging Face Transformers | BART | Wikipedia API | ROUGE | Streamlit

IMPACT:
Transforms unstructured textual data into searchable knowledge and concise insights.
Enables faster information discovery and decision-making from large document collections.
Demonstrates a scalable Retrieval-Augmented Generation (RAG-style) pipeline suitable for enterprise knowledge bases, research assistants, and intelligent search applications.
