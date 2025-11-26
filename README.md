🌐 Local LLM Web Content Summarizer

Day-1 Practice: Running LLM Model (Ollama) Locally On Host Machine And Summarize The Website Content

This repository demonstrates how to build a simple, cost-effective, and entirely private workflow for summarizing web content using a local Large Language Model (LLM) powered by Ollama and Python.

It's designed as a practical "Day-1" exercise for anyone starting with local LLM deployment and custom agent creation.

✨ Features

    100% Local Inference: All summarization happens on your machine using Ollama, eliminating API costs and ensuring data privacy.

    Web Scraping Integration: Includes a Python utility to fetch and process raw HTML content from a target URL.

    Structured Output: Uses prompt engineering to instruct the LLM to provide clean, structured summaries and key entity extraction.

    OpenAI Compatibility: Leverages the openai Python library's compatibility with the Ollama API.

⚙️ Prerequisites

Before you begin, ensure you have the following installed and configured:

    Python 3.x: (e.g., Python 3.9+)

    Ollama: The platform to run LLMs locally.

        Download and install Ollama for your OS (macOS, Windows, or Linux).

    Model: Pull the necessary model using the Ollama command line. This project uses llama3.2 (you can substitute with any other compatible model).

    
