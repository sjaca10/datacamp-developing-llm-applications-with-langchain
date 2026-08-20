# Building a retrieval prompt template

## Exercise

Now your documents have been ingested into vector database and are ready for retrieval, you'll need to design a chat prompt template to combine the retrieved document chunks with the user input question.

The general structure of the prompt has already been provided; your goal is to insert the correct input variable placeholders into the `message` string and convert the string into a chat prompt template.

## Instructions

- Complete the message string to add a placeholder for dynamic insertion of the retrieved documents called `context` and user input question `question`.
- Create a chat prompt template from `message` using the `.from_messages()` method with the "human" role.
