# Integrating custom tools with agents

## Exercise

Now that you have your tools at-hand, it's time to set up your agentic workflow! You'll again be using a ReAct agent, which, recall, reasons on the steps it should take, and selects tools using this context and the tool descriptions. An `llm` has already been defined for you that uses OpenAI's `gpt-4o-mini` model

## Instructions

- Create a ReAct agent using `create_react_agent()` with `llm` and a list containing your `retrieve_customer_info` tool.
- Invoke the agent with `agent.invoke()` on the input provided.
- Print the content from the final message.
