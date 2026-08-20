# Implementing few-shot prompting

## Exercise

Time to combine your components together into a chain! The few-shot prompt you created in the previous exercise is still available for you to use, along with `examples` and `example_prompt`.

All of the LangChain classes necessary for completing this exercise have been pre-loaded for you.

## Instructions

- Instantiate an OpenAI chat LLM using the `ChatOpenAI` class.
- Create a chain from the prompt template and LLM using the `|` operator, then invoke it using the `.invoke()` method.
