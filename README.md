# Academic Document RAG

An AI-powered **Retrieval-Augmented Generation (RAG)** system that allows users to upload academic documents such as textbooks and research papers and ask questions about their content.

## How It Works

```text
PDF Document
     ↓
Mistral OCR
     ↓
Text Extraction
     ↓
Gemini Embeddings
     ↓
Pinecone Vector Database
     ↓
Semantic Retrieval
     ↓
Gemini
     ↓
Answer
```

## Features

* Upload academic PDF documents
* Extract text using **Mistral OCR**
* Generate embeddings using **Google Gemini**
* Store and retrieve content using **Pinecone**
* Answer questions using **RAG**
* Retrieve relevant sections and summarize document content

## Technologies

**n8n · Mistral OCR · Google Gemini · Pinecone · RAG · Embeddings**

## Example Questions

* *Summarize page 24.*
* *Which page discusses overfitting?*
* *Explain CNN architecture from the textbook.*
* *What does the paper say about RAG?*

## Project Structure

```text
Academic-Document-RAG/
|--workflows_images/
|   |-- Academic_Document_OCR.png
|   |-- Academic_Document_Preprocessing.png
|   |-- Academic_Document_RAG.png
├── workflows/
│   ├── Academic_Document_OCR.json
│   ├── Academic_Document_Preprocessing.json
│   └── Academic_Document_RAG.json
└── README.md
```

> **Note:** API credentials are not included. Users must configure their own Gemini, Mistral, Pinecone, and n8n credentials to run the workflows.
