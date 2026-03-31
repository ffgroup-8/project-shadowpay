# Project Shadowpay — Docs

Drop client documents here as they are received. Reference them in CLAUDE.md using `@docs/filename`.

## Expected Files
- `brand-guidelines.md` (or .pdf) — Brand colors, fonts, logo rules, voice & tone
- `content-strategy.md` — Content pillars, messaging framework, audience personas
- `client-brief.md` (or SOW) — Project scope, deliverables, timeline, goals

## How to Reference in Claude Code
In CLAUDE.md or any session, use:
```
@docs/brand-guidelines.md
@docs/content-strategy.md
@docs/client-brief.md
```
This loads the file into context on demand without bloating the base CLAUDE.md.
