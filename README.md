# Agent Skills

Custom skills used by Rob Zolkos in his day-to-day development workflow.

## Installation

The simplest way to install these skills to any of your agents is via [skills.sh](https://skills.sh):

```bash
npx skills add robzolkos/agent-skills
```

## Skills

### `/done`

Resets the working directory after completing a task. Ensures no uncommitted changes exist, switches to the default branch (`master` or `main`), and pulls the latest changes. Use this between tasks to maintain a clean working state.

### `/catchup`

Catch up on codebase changes by reviewing the diff from master and reading any relevant spec files that were modified.

### `/discovery`

Quick user-centric interview for time-poor stakeholders. Asks 5-10 focused questions about the problem, current workflow, pain points, and desired outcome. Writes a scannable discovery doc that can feed into `/interview` for technical deep-dive.

### `/interview`

Interactive planning tool that interviews you in depth about a plan or idea. Takes a file path or raw text, asks detailed questions about technical implementation, UI/UX, concerns, and tradeoffs, then writes the final spec to a file.

### `/plan2json`

Convert feature requirements into structured PRD items as JSON. Each item includes category, description, steps to verify, and a passes flag for tracking verification status.

### `/prime`

Prime yourself on a new codebase by listing all files and reading the README.
