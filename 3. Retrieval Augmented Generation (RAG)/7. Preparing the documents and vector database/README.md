# Preparing the documents and vector database

## Exercise

Over the next few exercises, you'll build a full RAG workflow to have a conversation with a PDF document containing the paper, *RAG VS Fine-Tuning: Pipelines, Tradeoffs, and a Case Study on Agriculture* by Balaguer et al. (2024). This works by splitting the documents into chunks, storing them in a vector database, defining a prompt to connect the retrieved documents and user input, and building a retrieval chain for the LLM to access this external data.

In this exercise, you'll prepare the document for storage and ingest them into a Chroma vector database. You'll use a `RecursiveCharacterTextSplitter` to chunk the PDF, and ingest them into a Chroma vector database using an OpenAI embeddings function. As with the rest of the course, you don't need to provide your own OpenAI API key.

The following classes have already been imported for you: `RecursiveCharacterTextSplitter`, `Chroma`, and `OpenAIEmbeddings`.

## Instructions

- Split the documents in data using a `RecursiveCharacterTextSplitter` with a `chunk_size` of `300` and `chunk_overlap` of `50`.
- Use the `.from_documents()` method to embed and ingest the documents into a Chroma vector database with the provided OpenAI embeddings function.
- Configure `vectorstore` into a retriever object that returns the top 3 documents for use in the final RAG chain.
