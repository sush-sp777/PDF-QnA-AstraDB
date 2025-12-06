# PDF Question Answering with Astra DB, HuggingFace, and Groq LLM

This repository contains simple RAG pipeline that allows you to **ask questions about a PDF**. It uses **HuggingFace embeddings** to convert PDF chunks into vectors, stores them in **Astra DB (Cassandra)**, and uses **Groq LLM** for generating answers.

---

## Features

- Load and process PDFs using `PyPDFLoader`
- Split text into chunks with `RecursiveCharacterTextSplitter`
- Generate embeddings using **HuggingFace Sentence Transformers**
- Store and retrieve embeddings in **Astra DB** using `AstraDBVectorStore`
- Ask questions and get answers using **Groq LLM**

---

