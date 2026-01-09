# Simple Chatbot Server

A Pipecat server-side bot that connects to a Pipecat client, enabling a user to talk to the bot through their browser.


 **OpenAI Bot**

   - Uses gpt-4o for conversation
   - Requires `OPENAI_API_KEY`


## Setup

1. Configure environment variables

   Create a `.env` file:

   ```bash
   cp env.example .env
   ```

   Then, add your API keys:

   ```ini
   OPENAI_API_KEY=          # Your OpenAI API key (required for OpenAI bot)
   ```

2. Set up a virtual environment and install dependencies

   ```bash
   cd server
   uv sync
   ```

3. Run the bot:

   ```bash
   uv run bot-openai.py --transport daily
   ```

