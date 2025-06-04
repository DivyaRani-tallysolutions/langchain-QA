# PDF Question Answering with Scraping and Ollama LLM

This project scrapes web content, converts it into a PDF, and enables question answering (QA) on that PDF using retrieval-augmented generation (RAG) with LangChain and Ollama LLM.

---

## Features

- *Web scraping:* Downloads and extracts text from a Wikipedia page (or any URL).
- *PDF creation:* Saves scraped text as a formatted PDF file.
- *Document processing:* Splits PDF into chunks for better retrieval.
- *Embedding & indexing:* Converts text chunks into vector embeddings using HuggingFace.
- *Retrieval QA:* Uses Ollama LLM to answer questions directly and with context from the PDF.
