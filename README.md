# RAG Implementation Using LangChain and Trillvil Search Engine

This repository contains three implementations of Retrieval-Augmented Generation (RAG) using LangChain and the Trillvil search engine. The implementations progress from a basic RAG model to an advanced RAG model, and finally to an agent-based RAG model using the Trillvil search engine.

## Table of Contents

1. [Basic RAG](#basic-rag)
2. [Advanced RAG](#advanced-rag)
3. [Agent RAG Using TAVILY Search Engine](#agent-rag-using-TAVILY-search-engine)
4. [Setup and Installation](#setup-and-installation) 

## Basic RAG

The basic RAG implementation uses LangChain to integrate a retrieval component with a generative model. This approach allows for more accurate and contextually relevant responses by retrieving pertinent documents from a knowledge base before generating the response.

### Features
- Simple integration of retrieval and generation
- Uses LangChain for managing the components
- Provides a foundation for more advanced RAG implementations

## Advanced RAG

The advanced RAG builds on the basic implementation by enhancing the retrieval and generation processes. This version includes more sophisticated retrieval techniques and improved integration with the generative model.

### Features
- Enhanced retrieval mechanisms
- Improved integration with generative model
- Better performance and accuracy

## Agent RAG Using Trillvil Search Engine

The agent-based RAG implementation leverages the TAVILY search engine for retrieval. This version introduces an agent that uses the search engine to find the most relevant documents, which are then used to generate the final response.

### Features
- Utilizes Trillvil search engine for document retrieval
- Agent-based architecture for more dynamic and flexible interactions
- Superior retrieval and generation performance

## Setup and Installation

To run the implementations in this repository, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone git clone https://github.com/SaleemMalik632/RAG-Using-LangChain.git
    cd rag-langchain-trillvil
    ```

2. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables:**
    - Create a `.env` file in the root directory
    - Add your API keys and other necessary configurations

    Example:
    ```env
    LANGCHAIN_API_KEY=your_langchain_api_key
    TRILLVIL_API_KEY=your_trillvil_api_key
    ```