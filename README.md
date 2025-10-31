Overview

This project demonstrates a Retrieval-Augmented Generation (RAG) system for Generative AI using PDF documents as the knowledge source. The goal is to extract relevant information from PDFs and use a Large Language Model (LLM) to answer domain-specific questions accurately and contextually.

🔍 Objective

To build a pipeline that:

Loads and processes PDF documents related to Artificial Intelligence or research papers.

Splits the text into chunks for better retrieval.

Embeds the chunks into a vector database (Chroma, FAISS, etc.).

Retrieves relevant chunks based on user queries.

Passes the context to an LLM (like Llama 3, Groq, or OpenAI models) for generating answers.

🧩 Key Features

PDF-based text ingestion and vector storage.

Context-aware question answering using LLM.

Modular and extendable codebase.

Can integrate with any LLM backend (Groq, OpenAI, Anthropic, etc.).

🚀 Future Enhancements

Add source citation tracking to show document references in responses.

Integrate Streamlit UI for interactive query testing.

Implement real-time document updates with re-embedding.
