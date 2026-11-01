# AGENTS.md — Goldmine

Inherits the global `~/AI/AGENTS.md` and `~/AI/protocols.md`. Keep this file lean.

## What this project is
Goldmine is a single-page browser game (`index.html`) with ore and tile sprites in `assets/`
(copper, silver, gold, platinum, jackpot, bomb, safe, stone). Repo: `goldklangdesign/goldmine`.

## Critical must-knows
- **Living source of truth: `STATUS.md`.** It holds the current state, open items and everything waiting on
  David. Write decisions there in the same turn, never only in chat.
- **Handoffs: `docs/handoff/YYYY-MM-DD-<topic>.md`.**
- The agent runs from `~/Workspace/Other`, the parent folder. That folder is not a repo and holds unrelated
  personal files (photos, other small projects). Never commit or copy them into this repo (PII).
- Reminders hold only David's own personal to-dos. Goldmine work and "waiting on David" items go in `STATUS.md`.
  Anything for Reminders goes through the Orchestrator.

## How to work here
- Tracker: `STATUS.md`.
- No build step: open `index.html` in a browser.
