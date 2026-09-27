# Ep. 03 — Conversation memory, context window, and sliding window

**Language:** en

## Topic

Why the model forgets between calls, how to build a message history, what happens when context length is exceeded, and the minimum fix: a **sliding window**.

**Linear:** [CM-43](https://linear.app/caiomedeiros/issue/CM-43)

## Notebook progressions

1. Stateless calls → forgets
2. History list → remembers
3. Grow until context length exceeded
4. Sliding window → drop oldest, keep recent

## Folder layout

- `notebooks/03-conversation-memory-sliding-window.ipynb`

