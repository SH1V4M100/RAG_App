📄 PDF Question Answering System with RAG

This is a Retrieval-Augmented Generation (RAG) application that enables users to upload PDF documents, process their content into vector embeddings, and ask questions about the document using OpenAI's GPT-4. The system combines the power of OpenAI, FAISS, and Streamlit to deliver a seamless question-answering experience.

Features
Upload and Process PDFs:

Upload any PDF document.
Extracts text and splits it into manageable chunks.
Creates vector embeddings for efficient retrieval.
Ask Questions:

Query the content of the uploaded PDF.
Retrieves relevant text chunks and generates context-aware answers using GPT-4.
Email Verification:

Users must verify their email before accessing the application.
Emails are securely logged in a MongoDB database.
Streamlit Frontend:

Simple and interactive user interface for PDF uploads and querying.
Live Demo
Try the app here: https://ragapp-pdf.streamlit.app/