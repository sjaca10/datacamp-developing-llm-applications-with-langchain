# Hugging Face models in LangChain!

## Exercise

There are thousands of models freely available to download and use on Hugging Face. [Hugging Face](https://huggingface.co/models) integrates really nicely into LangChain via its partner library, `langchain-huggingface`, which is available for you to use.

In this exercise, you'll load and call the `crumb/nano-mistral` model from Hugging Face. This is a ultra-light LLM designed to be fine-tuned for greater performance.

## Instructions

- Import `HuggingFacePipeline` from `langchain_huggingface` to work with Hugging Face models.
- Define a text generation LLM by calling `HuggingFacePipeline.from_model_id()`.
- Set the `model_id` parameter to specify which Hugging Face model to use.
