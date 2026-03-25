## todo-persistence
### Requirements
1. `saveTodos()`: `localStorage.setItem('todos', JSON.stringify(todos))`
2. `loadTodos()`: `JSON.parse(localStorage.getItem('todos')) || []`
3. Call `saveTodos()` after add, delete, and toggle
4. On page load: `todos = loadTodos(); renderTodos();`
### Scenarios
- Given saved todos, When refreshing, Then todos reappear
- Given no saved data, When loading, Then empty list shows
- Given a todo is added, When checking localStorage, Then it contains the new todo
