# Recursively splitting by character

## Exercise

Many developers are using a recursive character splitter to split documents based on a specific list of characters. These characters are paragraphs, newlines, spaces, and empty strings, by default: `["\n\n", "\n", " ", ""]`.

Effectively, the splitter tries to split by paragraphs, checks to see if the `chunk_size` and `chunk_overlap` values are met, and if not, splits by sentences, then words, and individual characters.

Often, you'll need to experiment with different `chunk_size` and `chunk_overlap` values to find the ones that work well for your documents.

## Instructions

- Import the `RecursiveCharacterTextSplitter` class from `langchain_text_splitters`.
- Create a `RecursiveCharacterTextSplitter` instance with `separators=["\n", " ", ""]`, `chunk_size=24`, and `chunk_overlap=10`.
- Use the `.split_text()` method to split the `quote` and print the chunks and chunk lengths.
