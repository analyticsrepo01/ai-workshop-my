# DIY RAG (Retrieval-Augmented Generation) with Document AI and Vertex AI

This README provides an overview of building a DIY RAG system using Document AI and Vertex AI, as demonstrated in the `part_DIY_RAG_pdf.ipynb` notebook.

## Overview

This notebook guides you through the process of creating a Retrieval-Augmented Generation (RAG) system. The system extracts text from PDF documents using Document AI, generates embeddings using Vertex AI's text embedding models, and stores these embeddings for semantic search. This allows you to query the documents and retrieve relevant information to augment the responses of a Large Language Model (LLM).

## Objectives

The `part_DIY_RAG_pdf.ipynb` notebook covers the following objectives:

- **Document Processing:**
    - Using open-source libraries (PyPDF2, pdfreader) to extract text from PDF documents.
    - Using Document AI to process PDF documents and extract text.
    - Batch processing multiple documents using Document AI.
- **Embeddings Generation:**
    - Initializing Vertex AI and setting up the Embeddings API.
    - Converting text into embeddings using Vertex AI's `textembedding-gecko@003` model.
- **Data Preparation:**
    - Splitting text into smaller chunks for efficient retrieval.
    - Displaying the split text in a Pandas DataFrame.
- **Vector Search:**
    - Creating a Matching Engine Index.
    - Deploying the Index to an Index Endpoint.
    - Querying the created index for semantic similarity.
- **Question Answering:**
    - Importing a question bank from a BigQuery public dataset.
    - Combining questions with retrieved document content to create prompts for LLMs.
    - Evaluating different AI models (Gemini, PaLM) for question answering.

## Key Features Demonstrated

The notebook demonstrates the following key features:

- **PDF to Text Conversion:** Converting PDF documents to text using both open-source and Document AI methods.
- **Text Splitting:** Dividing large text into smaller, manageable chunks.
- **Embeddings Generation:** Creating vector embeddings of text chunks using Vertex AI's `textembedding-gecko@003` model.
- **Vector Search with Matching Engine:** Building and querying a vector index for semantic similarity search.
- **Integration with LLMs:** Using retrieved context to improve the accuracy and relevance of LLM responses.

## Getting Started

For detailed instructions and code examples, please refer to the `part_DIY_RAG_pdf.ipynb` notebook.
intro_multimodal_.ipynb
