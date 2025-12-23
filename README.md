# MoSPI Scraper + RAG Chatbot

## Overview
This project implements a Retrieval-Augmented Generation (RAG) chatbot using statistical data inspired by publications from the Ministry of Statistics and Programme Implementation (MoSPI), Government of India.

The chatbot answers user queries strictly based on the provided dataset using semantic search and language generation.

## Features
- Structured dataset ingestion
- ETL pipeline (cleaning, validation, chunking)
- SQLite-based document storage
- Semantic embeddings using SentenceTransformers
- FAISS vector database for retrieval
- RAG-based chatbot with source awareness

## Project Files
- `Chatbot.ipynb` – Complete Jupyter Notebook implementation
- Dataset used: Structured Excel-based dataset
- Vector search using FAISS

## How to Run
1. Install dependencies:

pip install pandas sentence-transformers faiss-cpu transformers torch
2. Open Jupyter Notebook:

jupyter notebook
3. Run all cells in `Chatbot.ipynb`
4. Use the `ask_question()` function to query the chatbot

## Notes
This implementation focuses on correctness of the RAG pipeline.  
The system can be extended with a web UI or API for production use.

## Author
Yashaswani
