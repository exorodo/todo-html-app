## Tasks
- [x] Add `saveTodos()` function: `localStorage.setItem('todos', JSON.stringify(todos))`
- [x] Add `loadTodos()` function: return `JSON.parse(localStorage.getItem('todos')) || []`
- [x] Call `saveTodos()` at end of `renderTodos()`
- [x] On init: `todos = loadTodos(); renderTodos();`
