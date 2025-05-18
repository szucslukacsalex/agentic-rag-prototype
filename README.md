# Agentic Retrieval-Augmented Generation Chat App

A conversational AI application prototype that uses agentic RAG techniques to provide informative responses based on retrieved documents.

## Overview

This application combines the power of Large Language Models (LLMs) with an agentic approach to Retrieval-Augmented Generation (RAG).

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/agentic-rag-prototype.git
cd agentic-rag-prototype

# Create and activate a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage

The application can be run through the Jupyter notebook:

1. Launch the notebook:
   ```bash
   jupyter notebook agentic-rag-proto.ipynb
   ```

2. Run all cells to initialize the application

3. Use the `chat_with_agent()` function to start interacting:
   ```python
   chat_with_agent()
   ```

4. Type your questions when prompted and view responses with their source documents

## How It Works

The system operates through the following process:

1. User query is received
2. The agentic component analyzes the query to determine information needs
3. Relevant documents are dynamically retrieved from the knowledge base
4. The LLM generates a comprehensive response using the retrieved context
5. Source documents are tracked and presented to the user for transparency

## Technologies

- Python
- LangChain and LangGraph for agent orchestration
- Vector database for document storage and retrieval
- Transformers/LLMs for natural language understanding and generation

## Project Structure

```
agentic-rag-prototype/
├── agentic-rag-proto.ipynb   # Main notebook with implementation
├── requirements.txt          # Project dependencies
└── README.md                 # Project documentation
```