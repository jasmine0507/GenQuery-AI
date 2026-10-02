#GenQuery-AI Powered Assistant

GenQuery-AI Powered Assistant is an AI-powered student assistance system designed to provide intelligent and context-aware answers to student queries.

The application combines an Angular/Ionic frontend, Django REST Framework backend, and Retrieval-Augmented Generation (RAG) to provide answers based on uploaded documents.

## Project Objective

The main objective of this project is to provide students with an intelligent assistant that can:

- Ask questions through an AI chat interface
- Upload and process documents
- Retrieve relevant information from documents
- Generate context-aware answers
- Manage conversations
- Provide a simple and user-friendly interface

## Technologies Used

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

### AI and RAG

- Retrieval-Augmented Generation (RAG)
- Text Embeddings
- Vector Store
- Large Language Model (LLM)
- Document Processing
- Google Gemini API

## System Architecture

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

How RAG Works

Retrieval-Augmented Generation (RAG) allows the AI assistant to generate answers using relevant information retrieved from uploaded documents.

The process is:

1. User uploads a document.


2. The document is processed and its text is extracted.


3. The text is divided into smaller chunks.


4. Embeddings are generated for the chunks.


5. The embeddings are stored in a vector store.


6. The user asks a question.


7. Relevant document chunks are retrieved.


8. The retrieved context is provided to the language model.


9. The AI generates an answer based on the retrieved context.


10. The response and information sources are displayed to the user.



Main Features

Student login and authentication

Student dashboard

AI-powered question answering

Document upload

Document processing

RAG-based information retrieval

Context-aware responses

Conversation management

Source/chunk information for responses

Angular/Ionic user interface

Django REST API backend


Project Structure

SectionB_FullStack/
│
├── studentbeapi/
│   └── Django Backend
│
├── studentfe/
│   └── Angular/Ionic Frontend
│
├── docs/
│   └── PROJECT_DOCUMENT.md
│
├── project.json
├── README.md
└── .gitignore

Backend

The backend is developed using Python, Django, and Django REST Framework.

It provides APIs for:

Authentication

Document processing

Conversation management

AI question answering

RAG-based retrieval


Frontend

The frontend is developed using Angular and Ionic.

It provides:

Student dashboard

Document upload interface

AI assistant chat interface

Conversation interaction

AI response and source display


AI Assistant

The AI assistant uses Google Gemini along with the RAG pipeline to generate responses based on relevant project documents.

API credentials should be stored securely using environment variables and should not be committed to the repository.

Setup

Backend

Navigate to the backend directory:

cd studentbeapi

Create and activate a Python virtual environment, install the required dependencies, configure environment variables, and run the Django development server.

Frontend

Navigate to the frontend directory:

cd studentfe

Install the required Node.js dependencies:

npm install

Run the Ionic/Angular development server using the project's configured command.

Environment Variables

Sensitive credentials such as API keys should be stored in environment variables.

Example:

GEMINI_API_KEY=your_api_key_here

Do not commit actual API keys or other sensitive credentials to GitHub.

Project Status

The project includes a working student dashboard, document upload functionality, AI assistant interaction, document-based retrieval, and context-aware AI responses.

Future Enhancements

Improved document processing

Better retrieval accuracy

Support for additional document formats

Conversation history improvements

Enhanced authentication and authorization

Improved UI/UX

Deployment to a cloud environment


Conclusion

GenQuery-AI Powered Assistant demonstrates the integration of modern web technologies, document processing, Retrieval-Augmented Generation, vector search, and large language models to build an intelligent student assistance platform.

