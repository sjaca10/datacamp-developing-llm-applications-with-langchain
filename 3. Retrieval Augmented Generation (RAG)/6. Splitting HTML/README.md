# Splitting HTML

## Exercise

In this exercise, you'll split an HTML containing an executive order on AI created by the US White House in October 2023. To retain as much context as possible in the chunks, you'll split using larger `chunk_size` and `chunk_overlap` values.

All of the LangChain classes necessary for completing this exercise have been pre-loaded for you.

## Instructions

- Create an `UnstructuredHTMLLoader` for `white_house_executive_order_nov_2023.html`, and load it into memory.
- Set a `chunk_size` of `300` and a `chunk_overlap` of `100`.
- Create a `RecursiveCharacterTextSplitter` splitting on the `'.'` character, and use the `.split_documents()` method to split `data` and print the chunks.
