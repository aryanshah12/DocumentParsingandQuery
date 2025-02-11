
# document-parser

`document-parser` is a tool designed to split a structured document into smaller chunks and export them as separate files. This process utilizes `regex` and `langchain`, an open-source framework that stores these chunks as embeddings (vector representations of the text) in a vector database. We use PineconeDB for our vector database. This tool is particularly useful for searching and retrieving information from large documents and has significant use-cases in GPT/LLM evaluation.

## Prerequisites
OpenAI API and Pinecone API key

