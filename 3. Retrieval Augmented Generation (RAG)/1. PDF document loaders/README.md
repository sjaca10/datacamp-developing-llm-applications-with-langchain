# PDF document loaders

## Exercise

To begin implementing Retrieval Augmented Generation (RAG), you'll first need to load the documents that the model will access. These documents can come from a variety of sources, and LangChain supports document loaders for many of them.

In this exercise, you'll use a document loader to load a PDF document containing the paper, *RAG VS Fine-Tuning: Pipelines, Tradeoffs, and a Case Study on Agriculture* by Balaguer et al. (2024).

Note: `pypdf`, a dependency for loading PDF documents in LangChain, has already been installed for you.

## Instructions

- Import the appropriate class for loading PDF documents in LangChain.
- Create a document loader for the `'rag_vs_fine_tuning.pdf'` document, which is available in the current directory.
- Load the document into memory to view the contents of the first document, or page.
