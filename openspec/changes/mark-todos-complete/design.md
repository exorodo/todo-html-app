## Technical Approach
- Add `.completed` CSS class to existing styles
- In `renderTodos()`, set `li.className = todo.completed ? 'completed' : ''`
- Add `li.style.cursor = 'pointer'` and click listener that flips `todo.completed` and re-renders
