# Chat prompt templates

## Exercise

Given the importance of chat models in many LLM applications, LangChain provides functionality for creating prompt templates to structure messages to different chat roles.

The `ChatPromptTemplate` class has already been imported for you, and an LLM has already been defined.

## Instructions

- Use `ChatPromptTemplate.from_messages()` to convert the role-message pairs into a chat prompt template.
- Assign appropriate roles to the messages provided to create a conversation pattern.
- Create an LCEL chain and invoke it with the input provided.
