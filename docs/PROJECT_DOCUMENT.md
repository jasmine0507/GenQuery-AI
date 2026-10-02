# GenQuery-AI Powered Assistant

## 1. Project Overview

GenQuery-AI Powered Assistant is an AI-powered student assistance system designed to provide intelligent and context-aware answers to student queries.

The system combines a modern Angular/Ionic frontend with a Python Django backend and Retrieval-Augmented Generation (RAG) technology.

## 2. Project Objective

The main objective of this project is to provide students with an intelligent assistant that can:

- Ask questions through an AI chat interface
- Upload and process documents
- Retrieve relevant information from documents
- Generate context-aware answers
- Manage conversations
- Provide a simple and user-friendly interface

## 3. Technologies Used

### Frontend

- Angular
- Ionic
- TypeScript
- HTML
- SCSS

### Backend

- Python
- Django
- Django REST Framework

### Artificial Intelligence

- Retrieval-Augmented Generation (RAG)
- Text Embeddings
- Vector Store
- Large Language Model (LLM)
- Document Processing
- Google Gemini API

## 4. System Architecture

```text
User
 |
 v
Angular/Ionic Frontend
 |
 v
Django REST API
 |
 v
Document Processing
 |
 v
RAG Pipeline
 |
 +--> Document Extraction
 |
 +--> Text Chunking
 |
 +--> Embeddings
 |
 +--> Vector Store
 |
 v
Relevant Context
 |
 v
Large Language Model
 |
 v
AI Generated Response
 |
 v
User

5. RAG Workflow

Retrieval-Augmented Generation (RAG) is used to provide answers based on information retrieved from uploaded documents.

The workflow is:

1. User uploads a document.


2. The document is processed and text is extracted.


3. The extracted text is divided into smaller chunks.


4. Embeddings are generated for the text chunks.


5. The embeddings are stored in a vector store.


6. The user asks a question through the AI assistant.


7. Relevant document chunks are retrieved.


8. The retrieved context is provided to the language model.


9. The language model generates an answer using the retrieved context.


10. The answer and relevant sources are displayed to the user.



6. Document Processing

The system supports document-based information retrieval.

The document processing pipeline includes:

Document upload

Text extraction

Text chunking

Embedding generation

Vector storage

Relevant chunk retrieval


This allows the AI assistant to use information from the uploaded documents when answering questions.

7. AI Assistant

The AI Assistant allows students to ask questions through a chat interface.

The backend retrieves relevant information from the document collection and provides the retrieved context to the Gemini language model.

The generated response is then returned to the frontend and displayed to the student.

8. Main Features

Student authentication

Student dashboard

AI-powered question answering

Document upload

Document processing

RAG-based information retrieval

Context-aware responses

Conversation management

Source and chunk information

Angular/Ionic user interface

Django REST API backend


9. Frontend Module

The frontend is developed using Angular and Ionic.

Main frontend components include:

Login page

Signup page

Student dashboard

Document upload page

AI assistant interface

Authentication service

API service


The frontend communicates with the Django REST API to perform authentication, document processing, and AI-related operations.

10. Backend Module

The backend is developed using Python, Django, and Django REST Framework.

The backend manages:

Student authentication

Document processing

Conversation management

API endpoints

RAG pipeline

Embeddings

Vector store

AI response generation


11. Project Structure

SectionB_FullStack/
|
+-- studentbeapi/
|   +-- studentapi/
|   +-- studentapp/
|   +-- manage.py
|   +-- rag components
|   +-- document processing
|
+-- studentfe/
|   +-- Angular/Ionic application
|   +-- pages
|   +-- services
|   +-- assets
|
+-- docs/
|   +-- PROJECT_DOCUMENT.md
|
+-- README.md
+-- project.json
+-- .gitignore

12. Security and API Key Management

Sensitive information such as API keys, passwords, and environment-specific configuration should not be committed to the GitHub repository.

API credentials should be stored using environment variables.

Example:

GEMINI_API_KEY=your_api_key_here

Actual API keys should never be included in project documentation or source code committed to GitHub.

13. Expected Output

The system provides students with an AI-powered conversational interface.

The assistant retrieves relevant information from uploaded documents and generates context-aware responses.

The response can also display the information sources or document chunks used to generate the answer.

14. Future Enhancements

Future improvements may include:

Support for additional document formats

Improved document retrieval accuracy

Enhanced conversation history

Improved authentication and authorization

Better user interface and experience

Cloud deployment

Additional AI capabilities


15. Conclusion

GenQuery-AI Powered Assistant demonstrates the integration of modern web technologies, document processing, Retrieval-Augmented Generation, vector search, and large language models to create an intelligent student assistance platform.

The project provides a practical example of how AI and RAG technology can be integrated with a full-stack web application to provide document-based question answering for students.

 