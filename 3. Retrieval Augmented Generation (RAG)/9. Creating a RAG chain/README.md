# Creating a RAG chain

## Exercise

Now to bring all the components together in your RAG workflow! You've prepared the documents and ingested them into a Chroma database for retrieval. You created a prompt template to include the retrieved chunks from the academic paper and answer questions.

The prompt template you created in the previous exercise is available as `prompt_template`, an OpenAI model has been initialized as `llm`, and the code to recreate your `retriever` has be included in the script.

## Instructions

- Create an LCEL chain using the pipe operator (`|`) to connect `retriever`, `prompt_template`, and `llm` in sequence.
- The chain should map the retriever to `"context"` and user input to `"question"`.
- Invoke the chain using the `.invoke()` method on the question provided.
