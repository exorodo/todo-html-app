## Technical Approach

Extend `index.html` with input HTML, CSS, and JS logic.

### Data Model
```js
let todos = [];
// Each: { id: Date.now(), text: string, completed: false }
```

### Functions
- `addTodo()`: reads input, validates non-empty, pushes to array, calls `renderTodos()`, clears input
- `renderTodos()`: clears `#todo-list` innerHTML, loops `todos`, creates `<li>` per item

### Event Binding
- Input `keydown` → Enter → `addTodo()`
- Button `click` → `addTodo()`
