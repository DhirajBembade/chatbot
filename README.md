# Langchain Chatbot

This project is a demonstration of a chatbot built using Langchain and OpenAI's GPT-3.5-turbo model. The chatbot is designed to assist users by responding to their queries in a helpful manner.

## Features

- Utilizes OpenAI's GPT-3.5-turbo model for generating responses.
- Built with Streamlit for a user-friendly web interface.
- Supports Langchain for prompt templates and output parsing.

## Setup and Installation

Follow these steps to set up and run the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/DhirajBembade/chatbot.git
   cd chatbot
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up environment variables:
   - Create a `.env` file in the project root directory.
   - Add the following environment variables to the `.env` file:
     ```
     LANGCHAIN_API_KEY=<your_langchain_api_key>
     OPENAI_API_KEY=<your_openai_api_key>
     LANGCHAIN_PROJECT="Tutorial1"
     ```

5. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## Using the Chatbot

Once the Streamlit app is running, you can interact with the chatbot through the web interface. Simply enter your query in the input box, and the chatbot will respond with a helpful answer.

The chatbot is designed to assist with a variety of queries, providing accurate and relevant information based on the input provided.
