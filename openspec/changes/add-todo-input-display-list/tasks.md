## Tasks

- [x] Add `<input type="text" id="todo-input" placeholder="What needs to be done?">` and `<button id="add-btn">Add</button>` inside `#input-area`
- [x] Style `#input-area` as flex row with gap; style input (flex:1, border, padding, radius); style button (accent bg, white text, no border, radius, cursor pointer)
- [x] Add JS: `let todos = [];`
- [x] Add JS: `addTodo()` — read input value, trim, reject empty, push `{id: Date.now(), text, completed: false}`, call `renderTodos()`, clear input
- [x] Add JS: `renderTodos()` — clear `#todo-list`, loop todos, create `<li>` with text, append to list
- [x] Bind Enter key on `#todo-input` to `addTodo()`
- [x] Bind click on `#add-btn` to `addTodo()`
- [x] Style `#todo-list li` with padding, border-bottom, background white
