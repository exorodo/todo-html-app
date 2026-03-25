## todo-filter
### Requirements
1. Three buttons in `#filters`: All, Active, Completed
2. `let filter = 'all'` state variable
3. `renderTodos()` applies filter before rendering
4. Active button has `.active` class with accent background
5. Clicking a filter sets state and re-renders
### Scenarios
- Given mixed todos, When clicking Active, Then only non-completed show
- Given mixed todos, When clicking Completed, Then only completed show
- Given any filter, When clicking All, Then all todos show
