# UltaBot

A CLI chatbot with decent features. Built by Sagar.

<!DOCTYPE html>
<html>
<body>
    <video width="100%" controls autoplay muted>
        <source src="https://drive.google.com/file/d/1CIORjm43SXTVOasRCCBD-gOoIyYfa4_a/view?usp=sharing" type="video/mp4">
    </video>
</body>
</html>

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
