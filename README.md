# **Summarize Documents using RAG, LangChain, and LLMs**

Build a **document summarization pipeline** using:
- **LangChain** for orchestration
- **RAG (Retrieval-Augmented Generation)** architecture
- **LLMs (like OpenAI, Hugging Face)** for summarization

Step-by-step:
1. Environment setup
2. Loading and chunking private documents
3. Creating vector embeddings and setting up a retriever
4. Using LangChain and LLMs to summarize content
5. Wrapping it in a user interface (optional)

## Setup

This project need to use the following libraries:

*   [`ibm-watsonx-ai`](https://ibm.github.io/watson-machine-learning-sdk/index.html) for using LLMs from IBM's watsonx.ai
*   [`LangChain`](https://www.langchain.com/) for using its different chain and prompt functions
*   [`Hugging Face`](https://huggingface.co/models?other=embeddings) and [`Hugging Face Hub`](https://huggingface.co/models?other=embeddings) for their embedding methods for processing text data
*   [`SentenceTransformers`](https://www.sbert.net/) for transforming sentences into high-dimensional vectors
*   [`Chroma DB`](https://www.trychroma.com/) for efficient storage and retrieval of high-dimensional text vector data
*   [`wget`](https://pypi.org/project/wget/) for downloading files from remote systems
