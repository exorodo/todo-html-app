## todo-toggle
### Requirements
1. Click on `<li>` toggles `todo.completed` between true/false
2. `.completed` class: `text-decoration: line-through; opacity: 0.5`
3. `renderTodos()` adds `.completed` class when `todo.completed === true`
4. Cursor pointer on list items

### Scenarios
- Given an active todo, When clicked, Then it shows strikethrough and dimmed
- Given a completed todo, When clicked again, Then strikethrough is removed
