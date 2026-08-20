# Splitting by character

## Exercise

A key process in implementing Retrieval Augmented Generation (**RAG**) is splitting documents into chunks for storage in a vector database.

There are several splitting strategies available in LangChain, some with more complex routines than others. In this exercise, you'll implement a *character text splitter*, which splits documents based on characters and measures the chunk length by the number of characters.

Remember that there is no ideal splitting strategy, you may need to experiment with a few to find the right one for your use case.

## Instructions

- Import the `CharacterTextSplitter` class from `langchain_text_splitters`.
- Create a `CharacterTextSplitter` instance with `separator="\n"`, `chunk_size=24`, and `chunk_overlap=10`.
- Use the `.split_text()` method to split the quote and print the chunks and chunk lengths.
