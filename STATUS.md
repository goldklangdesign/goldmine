Active: Home Mini (MacBook = backup)

# Goldmine status

Living source of truth for Goldmine. Project work and anything waiting on David go here, not in Apple Reminders.

## Current state (2026-11-01)
- Single-page browser game: `index.html` plus ore and tile sprites in `assets/`. Last commit `4b0866a` (2026-02-20).
- Unfinished work on the "big win" celebration (tiered celebration overlay, particles, screen shake, sound,
  payout counter; about 520 lines in `index.html`, last edited 2026-03-13) was never committed. On 11-01 it was
  saved to branch `wip/big-win-celebration` and pushed. It is still an uncommitted change on `main` locally, as
  it was before.
- Agent: Goldmine (Remote Control name fixed as `Goldmine`). LaunchAgent `com.davidgoldklang.goldmine-claude`
  runs `~/bin/project-claude-start-continue.sh`, so restarts use `--continue`.

## Waiting on David
**Parked (David, 2026-11-01): very low priority. Nothing below is owed; don't raise it with him until he
un-parks Goldmine. Leave `wip/big-win-celebration` as is.**
- Safeguard hooks (SessionStart / Stop) aren't installed. A peer can't approve config changes, and the agent's
  folder is `~/Workspace/Other`, not this repo, so a `goldmine/.claude/settings.json` wouldn't load. Decide where
  they go: point the LaunchAgent at `~/Workspace/Other/goldmine`, or add `~/Workspace/Other/.claude/settings.json`.
- Decide what happens to `wip/big-win-celebration`: finish it, merge it, or drop it.

## Open items
- None beyond the above.
