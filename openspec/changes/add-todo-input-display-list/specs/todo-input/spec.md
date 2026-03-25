## todo-input

### Requirements
1. Text input inside `#input-area` with placeholder "What needs to be done?"
2. Add button next to input
3. Pressing Enter in input calls `addTodo()`
4. Clicking Add button calls `addTodo()`
5. Empty or whitespace-only input is rejected (no empty todos)
6. Input clears after successful add

### Scenarios
- Given the input has text, When I press Enter, Then a todo is added and input clears
- Given the input has text, When I click Add, Then a todo is added and input clears
- Given the input is empty, When I press Enter, Then nothing happens
