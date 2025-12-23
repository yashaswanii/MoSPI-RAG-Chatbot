## Submission Notes

### What Worked
- Built a complete RAG chatbot pipeline using a structured dataset
- Implemented text chunking, embeddings, and FAISS-based retrieval
- Chatbot answers are grounded strictly in the dataset
- Entire pipeline runs end-to-end in a Jupyter Notebook

### What Didn’t Work / Limitations
- Live web scraping was not enabled to keep the notebook lightweight
- No web UI was added; interaction is via notebook function calls
- Dataset size is limited for demonstration purposes

### What I Would Do Next
- Add incremental web scraping from MoSPI website
- Integrate LLaMA 3 using Ollama
- Expose the chatbot via FastAPI
- Add a simple web UI (Streamlit)
- Dockerize the full pipeline
