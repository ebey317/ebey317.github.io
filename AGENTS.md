# AGENTS.md

This file gives AI coding agents (Claude Code, Cursor, Codex, Hermes, etc.) the
context they need to work productively in this repo. Read it before touching
anything.

## What this project is

Personal portfolio site for Elijah Wilkins — Applied AI Engineer.

## Repository layout

Top-level layout:


Key files:
- `AGENTS.md`
- `CODE_OF_CONDUCT.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `index.html`

## Hard rules for agents

- `index.html` is hand-edited. No frameworks, no bundlers. Keep it static.
- If you add a project card, link to the actual repo, not a placeholder.

## Making a safe change

1. Read `README.md` first.
2. Match the project's existing style — read two adjacent files before writing yours.
3. If there is a `CLAUDE.md`, it overrides this file for Claude-specific guidance.
4. Run the test suite (`make test`, `pytest`, or repo-equivalent). If there is no test suite, say so in the PR.
5. Keep `git status` clean — no stray `.bak`, log, or debug files staged.

## Common failure modes

- Don't introduce a build step or preprocessor — this repo is intentionally one HTML file.

## Project status

This is a public repository. I welcome issues and pull requests — see `CONTRIBUTING.md`
for guidelines and `SECURITY.md` for reporting vulnerabilities.
