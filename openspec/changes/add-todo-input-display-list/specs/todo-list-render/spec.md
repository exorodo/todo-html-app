## todo-list-render

### Requirements
1. `todos` JS array stores objects: `{ id: Date.now(), text, completed: false }`
2. `renderTodos()` clears `#todo-list` and rebuilds `<li>` for each todo
3. Each `<li>` shows the todo text
4. Todos display in insertion order (oldest first)

### Scenarios
- Given no todos, When viewing the list, Then `#todo-list` is empty
- Given 3 todos added, When viewing the list, Then 3 `<li>` elements appear in order
