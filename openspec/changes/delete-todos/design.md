## Technical Approach
- `<li>` becomes flex container with text span + delete button
- Delete button click uses `e.stopPropagation()` to avoid triggering toggle
- `deleteTodo(id)`: filters `todos` array, calls `renderTodos()`
