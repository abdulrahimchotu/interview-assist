# Simple Chatbot


This repository demonstrates a simple AI chatbot with real-time audio interaction.


**OpenAI Bot**

   - Uses gpt-4o for conversation
   - Requires OpenAI API key



## Client 





**React**

   - Basic impelmentation using [Pipecat React SDK](https://docs.pipecat.ai/client/react/introduction)
   - Demonstrates the basic client principles with Pipecat React





## Quick Start

### First, start the bot server:

Follow the instructions in the [server directory](server/).

### Next, connect using client app:

- [React Guide](client/react/README.md)


## Important Note

The bot server must be running for any of the client implementations to work. Start the server first before trying any of the client apps.

## Requirements

- Python 3.10+
- Node.js 16+ (for JavaScript and React implementations)
- Daily API key
- OpenAI API key (for OpenAI bot)
- Gemini API key (for Gemini bot)
- ElevenLabs API key
- Modern web browser with WebRTC support

## Project Structure

```
simple-chatbot/
├── server/              # Bot server implementation
│   ├── assets           # Directory of sprite images
│   ├── bot-openai.py    # OpenAI bot implementation
│   ├── env.example      # Env variable example
│   ├── Dockerfile       # Dockerfile for building your image
│   ├── pcc-deploy.toml  # Pipecat Cloud: Deployment specification
│   ├── pyproject.toml   # Project specification
│   ├── README.md        # More specific server setup instructions
│   └── requirements.txt
└── client/              # Client implementations
    ├── react/           # Pipecat React client
```
