# Glassy To-Do

A polished, glassmorphism-inspired to-do app built with plain HTML, CSS, and JavaScript. It includes task creation, editing, completion, filtering, search, drag-and-drop reordering, local storage persistence, JSON import/export, and a live quote panel powered by an external API.

## Live Demo
Visit the deployed project here:
- GitHub Pages: https://sneh121.github.io/glassy-todo/
- GitHub Repository: https://github.com/sneh121/glassy-todo

## API used
This project uses the Quotable API to fetch inspirational quotes for the live API panel. The API is called at runtime with `fetch()` and displays a new quote each time the user refreshes or clicks the button.

## Run locally
Open [index.html](index.html) directly in a browser, or serve the folder with a simple static server:

```bash
python -m http.server 8000
```

Then visit http://127.0.0.1:8000/.
