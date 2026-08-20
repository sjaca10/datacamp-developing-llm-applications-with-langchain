# Creating custom tools

## Exercise

Now that you have a function for extracting customer data from the `customers` DataFrame, it's time to convert this function into a tool that's compatible with LangChain agents.

## Instructions

- Add the `@tool` decorator before the function definition to convert it into a LangChain tool.
- Print the tool's arguments using the `.args` attribute on the tool (e.g., `tool_name.args`).
