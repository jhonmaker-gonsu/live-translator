# live-translator

Single-page live translation tool for personal use. It sends microphone audio to a realtime translation API (OpenAI or Google Gemini, selectable) and shows/plays Japanese.

- The page contains no API key and stores none: a key is typed (or autofilled by the browser's password manager) and kept in memory only.
- Only the chosen source language and engine are saved in the browser (localStorage).
