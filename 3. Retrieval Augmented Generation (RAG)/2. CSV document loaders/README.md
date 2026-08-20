# CSV document loaders

## Exercise

Comma-separated value (CSV) files are an extremely common file format, particularly in data-related fields. Fortunately, LangChain provides different document loaders for different formats, keeping almost all of the syntax the same!

In this exercise, you'll use a document loader to load a CSV file containing data on FIFA World Cup international viewership. If you're interested in the full analysis behind this data, check out [How to Break FIFA](https://fivethirtyeight.com/features/how-to-break-fifa/).

## Instructions

- Import the appropriate class for loading CSV documents in LangChain.
- Create a document loader for the `'fifa_countries_audience.csv'` document, which is available in the current directory.
- Load the documents into memory to view the contents of the first document.
