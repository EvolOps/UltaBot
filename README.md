# UltaBot

A CLI chatbot with decent features. Built by Sagar.

<p align="center">
  <img
    src="https://aider.chat/assets/screencast.svg"
    alt="aider screencast"
  >
</p>

## Features

-   **Chat**: Talks to AI models.
-   **Voice**: Not right now. Development phase.
-   **Memory**: ChromaDB for context. It remembers your chats
-   **APIs**: Weather, news, translation, etc. Though you gotta add your own APIs for it to work.
-   **Extensible**: Add your own stuff.


## Structure

```
src/
├── cli/            # Handles your input, formats our sass.
├── core/           # The brains (debatable).
├── config/         # Settings. Boring but necessary.
└── extensions/     # Voice, APIs, the fun stuff.
```
