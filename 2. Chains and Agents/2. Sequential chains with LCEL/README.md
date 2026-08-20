# Sequential chains with LCEL

## Exercise

With your prompt templates created, it's time to tie everything together, including the LLM, using chains and LCEL. An llm has already been defined for you that uses OpenAI's gpt-4o-mini model

For the final step of calling the chain, feel free to insert any activity you wish! If you're struggling for ideas, try inputting "play the harmonica".

## Instructions

- Create a sequential chain using LCEL that passes `learning_prompt` into the `llm`, and feeds the output into `time_prompt` for resending to the `llm`.
- The first part should create a dictionary with `"learning_plan"` as the key and the first chain as the value.
- Call the chain using the `.invoke()` method with the activity of your choice!
