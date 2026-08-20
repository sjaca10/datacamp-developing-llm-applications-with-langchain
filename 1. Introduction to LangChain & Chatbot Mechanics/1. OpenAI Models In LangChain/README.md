# OpenAI models in LangChain!

## Exercise

OpenAI's GPT-series models are some of the highest performing LLMs around. They are available via OpenAI's API, which you can easily interact with using LangChain.

Normally, using OpenAI's models would require a personal API key used for billing the cost of the models. In this course, you do not need to create or provide an OpenAI API key. The `"<OPENAI_API_TOKEN>"` placeholder will send valid requests to the API. If you make large number of requests in a short period, you may encounter a `RateLimitError`. If you see this, please pause for a moment and try again.

The `ChatOpenAI` class has already been imported.

## Instructions

- Define an OpenAI chat model using a LangChain class; leave the API key placeholder as it is.
- Invoke the LLM you defined to respond to the `prompt` provided (feel free to experiment with other prompts here).
