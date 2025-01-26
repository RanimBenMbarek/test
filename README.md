# Medical Chatbot

A Python-based Medical Chatbot that answers health-related queries by fetching relevant information from Wikipedia and generating responses using a pre-trained Llama language model. This project is intended to help users quickly get reliable information about medical topics.

## Features

- **Health-Related Queries**: Ask anything related to health and get useful insights.
- **Wikipedia Integration**: Fetches relevant Wikipedia articles to provide the latest information.
- **AI-Generated Answers**: Uses the Llama model for generating accurate, human-like responses to user queries.
- **Simple Command-Line Interface**: Easy interaction with the chatbot through a terminal or console.

## How It Works

1. **User Input**: The user asks a health-related question (e.g., symptoms of a disease).
2. **Fetch Wikipedia Summary**: The bot fetches a summary of the relevant Wikipedia article based on the question.
3. **Response Generation**: The bot uses a pre-trained Llama language model to generate a response from the fetched summary.
4. **Final Output**: The chatbot presents the generated response back to the user.

## Technologies Used

- **Wikipedia API**: To fetch articles and summaries for the health-related questions.
- **Sentence Transformers**: To create sentence embeddings for processing text data.
- **Llama (Causal Language Model)**: For generating AI-driven, human-like responses.
- **Python**: The programming language used for implementing the chatbot.
- **Transformers Library (Hugging Face)**: Provides access to pre-trained Llama models.

## Installation & Requirements

Make sure you have Python 3.7+ installed. Then, install the required dependencies:

```bash
pip install wikipedia sentence-transformers transformers torch
