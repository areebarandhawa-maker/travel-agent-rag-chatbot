# travel-agent-rag-chatbot
AI-powered Travel Agent Chatbot using RAG, ChromaDB, Groq API and Python
✈️ Travel Agent RAG Chatbot

An AI-powered Travel Agent Chatbot built using Python, Retrieval-Augmented Generation (RAG), ChromaDB, and the Groq API.

🚀 Project Overview

This project answers travel-related questions using information retrieved from a custom travel agency knowledge base. It combines semantic search with a Large Language Model (LLM) to generate context-based responses.

🛠️ Technologies Used
Python
Google Colab
Groq API
ChromaDB
PyPDF
Embeddings and semantic search
Retrieval-Augmented Generation (RAG)
🔍 Key Features
Load TXT and PDF documents.
Clean and split documents into manageable chunks.
Generate embeddings for semantic retrieval.
Store document chunks in ChromaDB.
Retrieve relevant information based on user queries.
Generate answers using an LLM and retrieved context.
Maintain recent conversation history.
Display source document information.
⚙️ RAG Workflow

Document Loading → Text Cleaning → Chunking → Embeddings → ChromaDB → Retrieval → LLM Response

▶️ How to Run
Open Travel_Agent_RAG.ipynb in Google Colab.
Install the required dependencies.
Add your Groq API key through Google Colab Secrets.
Run the notebook cells in order.
Ask travel-related questions through the chatbot.
🔐 API Key Security

Never upload API keys or credentials to GitHub. Store your Groq API key securely using Google Colab Secrets.

📌 Future Improvements
Integrate a Streamlit user interface.
Support additional travel documents.
Improve retrieval accuracy and source citations.
Deploy the chatbot as a web application.
👩‍💻 Author

Areeba Randhawa
