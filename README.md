# Agent Skills

Custom skills used by Rob Zolkos in his day-to-day development workflow.

## Skills

### `/done`

Resets the working directory after completing a task. Ensures no uncommitted changes exist, switches to the default branch (`master` or `main`), and pulls the latest changes. Use this between tasks to maintain a clean working state.

### `/catchup`

Catch up on codebase changes by reviewing the diff from master and reading any relevant spec files that were modified.

### `/interview`

Interactive planning tool that interviews you in depth about a plan or idea. Takes a file path or raw text, asks detailed questions about technical implementation, UI/UX, concerns, and tradeoffs, then writes the final spec to a file.

### `/prime`

Prime yourself on a new codebase by listing all files and reading the README.
