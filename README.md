# LLM Chat App - Chat with your PDFs 💬

This is a **Streamlit-based** web application that allows you to interact with PDFs using a **Large Language Model (LLM)**. It utilizes **OpenAI**, **LangChain**, and **FAISS** to let you upload a PDF, process it into chunks, and then ask questions based on the content of the PDF. The app leverages **OpenAI's API** to generate human-like responses.

## Features

- **Upload PDF Files**: You can upload a PDF, and the app will extract text and create embeddings.
- **Query the PDF**: Ask any questions based on the uploaded PDF, and the app will provide LLM-powered answers.
- **Vector Storage**: Utilizes FAISS for efficient similarity search among document chunks.
- **Embeddings Persistence**: Saves embeddings for faster access on subsequent queries of the same document.
