## Technical Approach
- Add buttons in `#filters` div
- `setFilter(f)`: sets `filter`, updates button classes, calls `renderTodos()`
- `renderTodos()`: `const filtered = filter === 'all' ? todos : todos.filter(...)` then renders filtered
