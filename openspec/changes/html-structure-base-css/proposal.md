## Why

We need the foundational HTML5 structure and CSS for a single-file Todo application. All subsequent features (input, list rendering, filters, persistence) depend on this skeleton being in place.

## What Changes

- Create `index.html` with valid HTML5 doctype, charset, viewport meta
- Add CSS reset (box-sizing, margin, padding zeroed)
- Define CSS custom properties for theming (--bg, --text, --accent, --border)
- Create centered app container (max-width 600px) with header
- Add placeholder sections for input area, todo list, and filters

## Capabilities

### New Capabilities
- `html-skeleton`: Base HTML5 document with responsive layout, CSS variables, and app container structure

### Modified Capabilities

## Impact

- Creates `index.html` — the single file all other tickets will modify
- No external dependencies, no build tools
