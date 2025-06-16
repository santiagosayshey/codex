# codex
Self-hostable, standards-agnostic note taking app designed for programmers.

A note-taking environment where your code examples actually run. Write markdown documentation with live, executable code blocks that show real output.
## How it works

- Write notes in markdown (`/md/`)
- Store code in separate files (`/code/`)
- Reference code in notes with ``` filename.ext ```
- Code executes via WebSocket and shows live output
- Supports web tech (HTML/CSS/JS), Node.js, and extensible to other runtimes

## Features

- **File-based**: No database, just files you own
- **Standards-agnostic**: Works with any language/framework
- **Self-hostable**: Run locally or deploy anywhere
- **Live execution**: Real output, not static examples
- **WebSocket communication**: Fast, real-time code execution