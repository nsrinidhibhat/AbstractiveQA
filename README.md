# Abstractive Question Answering

Abstractive question-answering focuses on the generation of multi-sentence answers to open-ended questions. It usually works by searching massive document stores for relevant information and then using this information to synthetically generate answers. This notebook demonstrates how to build an abstractive question-answering system. We need three main components:

- A vector index to store and run semantic search
- A retriever model for embedding context passages
- A generator model to generate answers
