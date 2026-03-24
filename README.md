# Knowledge engineering for AI usage

The aim of this project is to create a conversational agent that can answer questions about any GitHub repository. Think of it as your personal AI assistant for documentation and code. If you're familiar with DeepWiki, it's similar, but tailored to your GitHub repository.

For that, we need to:

- Download and process data from the repo
- Put it inside a search engine
- Make the search engine available to our agent

## Data retrieval and processing

The logic for data retrieval and processing is shown in Ingest_and_index_data.ipynb notebook

The first step is to download the data as a zip archive, process all the text data from there, and make it available for ingestion into a search engine later.

This project is part if AI Agents crash course by @Alexey Grigorev that you can check out at: https://alexeygrigorev.com/aihero/
