# Daily Task Tracker

Single-file browser app (`index.html`) for tracking daily tasks.

## Architecture

- Everything lives in one `index.html` — HTML, CSS, and JS are all inline
- No build step, no external dependencies, no server required
- Opens directly via `file://` protocol
- Tasks persist in `localStorage`

## Constraints

- **Single file**: Do not split into separate `.css` or `.js` files
- **No dependencies**: No frameworks, libraries, CDNs, or imports
- **No server**: Must work when opened as a local file (`file://`)
- **localStorage only**: All persistence uses `localStorage`

## Style

- Clean, minimal UI optimized for laptop screens
