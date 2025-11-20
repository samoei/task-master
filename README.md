

# Task Master 🔧

A beautiful, Git-inspired CLI task tracker built with Typer, Rich and uv.

Fast, type-safe, colorful, and actually fun to use — perfect for product managers who miss shipping code.

## Features (planned)

- `task add "Write OKRs" --due 2025-12-31 --priority high --tags okr planning`
- `task list --status pending --tag roadmap`
- `task done 3`
- `task edit 5 --add-tag blocked`
- Subcommands like Git: `task branch`, `task checkout`, `task merge` (for task dependencies later)
- Persistence in `~/.local/share/task-master/tasks.json` (or SQLite later)
- Rich tables, progress bars, markdown rendering in terminal
- Shell completion (zsh, bash, fish)

## Installation

```bash
uv tool install task-master
```

(or `pipx install task-master` when published)

## Development

```bash
git clone git@github.com:yourusername/task-master.git
cd task-master
uv sync
uv run task --help
```
## Screenshots (Coming Soon)

## Why another todo app?

Because every ex-engineer PM needs a weekend project to remember how good it feels to ship something that works.
Made with ❤️ by a PM who still writes code at 2 am.
