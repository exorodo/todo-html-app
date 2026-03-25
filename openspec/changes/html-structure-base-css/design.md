## Technical Approach

Single-file architecture: everything in `index.html` with inline `<style>` and `<script>` tags. No build tools, no external dependencies.

### CSS Strategy
- CSS custom properties for theming — easy to adjust colors globally
- System font stack: `-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`
- Mobile-first responsive: container adapts to viewport

### DOM Structure
```
<div class="app">
  <h1>Todo App</h1>
  <div id="input-area"></div>
  <ul id="todo-list"></ul>
  <div id="filters"></div>
</div>
```

### Decisions
- Single file over multi-file: simplicity, zero setup, easy to share
- CSS variables over hardcoded values: enables future theming
- Semantic HTML: `<ul>` for list, `<h1>` for title
