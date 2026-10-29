# RAG Application

A modular, enterprise-grade Retrieval-Augmented Generation (RAG) application.

## Architecture

The application follows a modular design pattern with clear separation of concerns:

1. **Data Loading** - Load documents from various sources
2. **Document Chunking** - Split documents into manageable chunks
3. **Embedding Generation** - Create vector embeddings for text
4. **Vector Storage** - Store and retrieve embeddings efficiently

## Project Structure
rag-application/
├── src/ # Source code
│ ├── config/ # Configuration management
│ ├── data_ingestion/# Data loading and chunking
│ ├── embeddings/ # Embedding generation
│ ├── vector_store/ # Vector database operations
│ └── utils/ # Utilities and helpers
├── tests/ # Unit and integration tests
├── data/ # Data storage
├── notebooks/ # Jupyter notebooks for exploration
└── logs/ # Application logs
.
.
.
.
.
.
