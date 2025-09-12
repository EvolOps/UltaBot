# UltaBot

A CLI chatbot with decent features. Built by Sagar.

## Features

-   **Chat**: Talks to AI models.
-   **Voice**: Not right now. Development phase.
-   **Memory**: ChromaDB for context. It remembers your chats
-   **APIs**: Weather, news, translation, etc. Though you gotta add your own APIs for it to work.
-   **Extensible**: Add your own stuff.

## Quick Start

```bash
git clone <this repo ofc>
cd UltaBot
pip install -r requirements.txt
cp env.template .env  # <- Edit this. Add your API keys.
python main.py
```

## Config (`/.env`)

The important bits:
```bash
DEEPSEEK_API_KEY/NIM_API_KEY="your-keys" #You need either Deepseek's keys or NVIDIA NIM's api key, if you don't have either of them... well, enjoy the pre-generated messages.
VOICE_ENABLED=false              # Still in development phase. Will update later... for sure. really,
MEMORY_PERSIST_DIR=./memory      # Where the bot's memory lives.
```

## Usage

Run it: `python main.py`
Talk to it. Type `/help` if you get lost. 

## Structure

```
src/
├── cli/            # Handles your input, formats our sass.
├── core/           # The brains (debatable).
├── config/         # Settings. Boring but necessary.
└── extensions/     # Voice, APIs, the fun stuff.
```

## Commands
-   `Python main.py` - Enter the prison?
-   `/exit` - Freedom.
