# RAG-Generative-AI-Solution
Assignment 1: Fixed-Size Chunking and Semantic Search
-------------------------------------------------------------------------------------------------------------------------------
**Description:** Reads one text file (10+ paragraphs), splits it into overlapping fixed-size chunks, embeds them, and retrieves the three most relevant chunks for a user question.

Assignment 2: Semantic Chunking, FAISS Vector DB and LLM Synthesis
-------------------------------------------------------------------------------------------------------------------------------
**Description:** Builds a basic RAG pipeline by loading three text files from different fields, splitting them into semantic chunks, converting the chunks into embeddings, and storing them in a FAISS vector database. It then accepts a natural language query, embeds it using the same model, performs cosine similarity search, and retrieves the top three most relevant chunks with their similarity scores and source file references.

Project:
-----------------------------------------------------------------------------------------------------------------------------
**Description:** Loads three text files from different domains, splits them into meaningful semantic chunks, generates embeddings using a pre-trained SentenceTransformer model, and stores the vectors and metadata in a persistent FAISS vector database. It then accepts a natural language question, retrieves the three most relevant chunks using cosine similarity, and provides them to an LLM to generate an answer based only on the retrieved context, along with the source references.
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -
**A Retrieval-Augmented Generation solution developed as part of the "Generative AI Solutions Development" training program at SDAIA.   
SDAIA Academy on GitHub: https://github.com/SDAIAAcademy**
