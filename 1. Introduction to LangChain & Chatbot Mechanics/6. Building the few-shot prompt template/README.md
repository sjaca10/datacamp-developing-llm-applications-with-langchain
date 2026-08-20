# Building the few-shot prompt template

## Exercise

With your examples in a structured format, it's now time to create the few-shot prompt template! You'll create a template that converts the question-answer pairs into the following format:
```
Question: Example question
Example Answer
```

All of the LangChain classes necessary for completing this exercise have been pre-loaded for you.

## Instructions

- Complete the prompt for formatting answers so it includes the `question` and `answer` keys.
- Create the few-shot prompt using `FewShotPromptTemplate` with `examples` and `example_prompt`.
- Complete the list of input variables based on the suffix provided.
