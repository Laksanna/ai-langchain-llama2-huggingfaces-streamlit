# AI Assistance For Website
This Streamlit application offers AI-driven website data retrieval and search capabilities using HuggingFace and Pinecone APIs. It processes user search queries and delivers relevant documents in response.

## Features

- **Session State Management:** Securely manages HuggingFace and  Pinecone API keys using Streamlit's session state.
- **Sidebar Input:** Allows users to input HuggingFace and Pinecone API keys.
- **Data Loading:** Fetches data from a website and indexes it in Pinecone.
- **Search Functionality:** Retrieves and displays relevant documents from Pinecone based on user queries.

## Key Components

- API Key Management: Securely captures and manages HuggingFace and Pinecone API keys.
- Data Loading to Pinecone:
    - Fetches data from a specified website.
    - Splits the data into manageable chunks.
    - Creates embeddings for the data chunks.
    - Pushes the embeddings and data chunks to Pinecone for indexing.

## Attachment

![image](https://github.com/user-attachments/assets/0efef3d0-e5c0-43fa-bcb2-e86b5d2de128)

