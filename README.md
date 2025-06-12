# customer_support_Agent

I am creating an custoper support ChatBot using Smol Agents Framework.

This repository contains a Customer Support AI Agent that leverages Retrieval-Augmented Generation (RAG) to provide accurate and context-aware responses to user queries based on company documentation.

## Features

- **Smol Agents Framework**: Modular and lightweight agent framework for building AI-powered assistants.
- **Retrieval-Augmented Generation (RAG)**: The agent retrieves relevant information from provided company documents and uses it to generate precise answers.
- **Custom Knowledge Base**: Easily upload or update company documents to keep the chatbot's knowledge up to date.

## How it Works

1. **Document Ingestion**: Upload your company documents (PDF, TXT, DOCX, etc.) to the knowledge base.
2. **Indexing**: The documents are processed and indexed for efficient retrieval.
3. **User Query**: When a user asks a question, the agent retrieves relevant document sections.
4. **Answer Generation**: The agent combines retrieved information with generative AI to provide a helpful response.

## Example Usage

1. Place your company documents in the `docs/` folder.
2. Run the agent: