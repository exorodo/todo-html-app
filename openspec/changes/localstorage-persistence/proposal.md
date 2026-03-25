## Why
Todos are lost on page refresh. Users expect their data to persist.

## What Changes
- Add `saveTodos()` and `loadTodos()` functions using localStorage
- Call save after every mutation (add, delete, toggle)
- Load and render on page init

## Capabilities
### New Capabilities
- `todo-persistence`: Save/load todos via localStorage
### Modified Capabilities
## Impact
- Modifies `index.html`: JS functions, init call
