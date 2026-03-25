## html-skeleton

Base HTML5 document with responsive layout, CSS variables, and app container.

### Requirements

1. Valid HTML5: `<!DOCTYPE html>`, `<html lang="en">`, `<meta charset="UTF-8">`, `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
2. CSS reset: `*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }`
3. CSS custom properties on `:root`: `--bg`, `--text`, `--accent`, `--border`, `--radius`
4. Body: system font stack, `background: var(--bg)`, `color: var(--text)`
5. App container: `max-width: 600px`, centered, with padding
6. Header: `<h1>Todo App</h1>`
7. Placeholder: `<div id="input-area"></div>`
8. Placeholder: `<ul id="todo-list"></ul>`
9. Placeholder: `<div id="filters"></div>`
10. All CSS inline in `<style>`, all JS inline in `<script>`

### Scenarios

- Given a browser, When opening index.html, Then a centered container with "Todo App" heading is visible
- Given a viewport under 600px, When viewing the page, Then the container fills width with padding
- Given the HTML source, When validating, Then no HTML5 errors are found
