# Chatbot
![WhatsApp Image 2024-12-14 at 14 03 57_eced19ee](https://github.com/user-attachments/assets/b2b75f53-0c75-4757-9d26-0e7ec5104c67)

**Objective:** Build an AI-powered chatbot to interact with uploaded PDF files by answering user questions.


**Technologies Used:**

Streamlit: For creating the web application interface.
PyPDF2: For extracting text from PDF files.
Sentence Transformers: For generating embeddings of the PDF content.
FAISS: For efficient similarity search on the embeddings.
Hugging Face Transformers: For generating chatbot responses (Mistral 7B model or equivalent).

**Key Features**
PDF Upload:
Users can upload a PDF through the Streamlit interface.
Text Extraction:
Extracts and processes text from PDF files using PyPDF2.
Chunking & Embedding:
Splits text into smaller chunks and generates embeddings using the SentenceTransformer model (all-MiniLM-L6-v2).
Semantic Search:
Implements FAISS for similarity matching to retrieve relevant text chunks.
Natural Language Processing:
Answers user questions based on context using the Mistral 7B model for text generation.
User-Friendly Interface:
Simple, interactive Streamlit UI for uploading files, typing queries, and viewing answers.

