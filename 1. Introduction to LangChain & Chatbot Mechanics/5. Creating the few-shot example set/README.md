# Creating the few-shot example set

## Exercise

`PromptTemplate` and `ChatPromptTemplate` are great for integrating variables, but struggle with integrating datasets containing many examples. This is where `FewShotPromptTemplate` comes in! In this exercise, you'll create a dataset, in the form of a list of dictionaries, to contain the follow question-answer pairs.

- Question: How many DataCamp courses has Jack completed?
- Answer: 36
- Question: How much XP does Jack have on DataCamp?
- Answer: 284,320XP
- Question: What technology does Jack learn about most on DataCamp?
- Answer: Python

In the next exercise, you'll convert this information into a few-shot prompt template.

## Instructions

- Create a list of dictionaries for the questions and answers provided, using the keys `"question"` and `"answer"`.
