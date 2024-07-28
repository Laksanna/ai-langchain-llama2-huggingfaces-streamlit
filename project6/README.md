# MCQ Quiz Creator App
This application generates multiple-choice questions (MCQs) from provided documents. It works by breaking documents into chunks, creating vector embeddings, conducting similarity searches, and using a language model to formulate questions.

## Features

- **Real-Time Question Generation:**
Provides instant generation of MCQs from the input documents, enhancing efficiency and productivity.
- **User-Friendly Interface:**
Features a straightforward and intuitive interface for easy document upload and question generation.
- **Document Processing:**
Breaks down provided documents into manageable chunks for easier analysis and question generation.
- **Similarity Search:**
Performs similarity searches on the vector embeddings to identify relevant content for question creation.

## Model Configuration
- **LLM (Language Model) Used:** `mistralai/Mistral-7B-Instruct-v0.2`
- **Embedding Model:** `all-MiniLM-L6-v2`

## Technologies Used
- LangChain: For building language model applications.
- Pinecone: For vector database management and similarity search.
