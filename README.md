# Glassy To-Do

A polished, glassmorphism-inspired to-do app built with plain HTML, CSS, and JavaScript. It supports task creation, editing, completion, filtering, search, drag-and-drop reordering, local data saving, import/export, and a live quote panel powered by an external API.

## API used
This project uses the Quotable API to fetch inspirational quotes for the live API panel. The API is called at runtime with `fetch()` and displays a new quote each time the user refreshes or clicks the button.

## Run locally
Open [index.html](index.html) directly in a browser, or serve the folder with a simple static server:

```bash
python -m http.server 8000
```

Then visit http://127.0.0.1:8000/.
