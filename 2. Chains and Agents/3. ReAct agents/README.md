# ReAct agents

## Exercise

Time to have a go at creating your own ReAct agent! Recall that ReAct stands for Reason and Act, which describes how they make decisions. In this exercise, you'll load the built-in `wikipedia` tool to integrate external data from Wikipedia with your LLM. An `llm` has already been defined for you that uses OpenAI's `gpt-4o-mini` model

Note: The `wikipedia` tool requires the `wikipedia` Python library to be installed as a dependency, which has been done for you in this case.

## Instructions

- Load the `"wikipedia"` tool using the `load_tools()` function.
- Define a ReAct agent using `create_react_agent()`, passing it the llm and tools to use.
- Run the agent on the input provided and print the content from the final message in response
