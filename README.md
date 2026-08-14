# The Glass Ball — Mobile

**Joelle's task & schedule app, on the phone that lives in her pocket.**
iPhone-primary PWA surface of [The Glass Ball](https://github.com/Driver-cyber/glass-ball)
— catch the glass, let the rubber bounce.

This repo is the daily driver: a single-file vanilla HTML app
(`src/index.html`) plus its three PWA companions (`manifest.webmanifest`,
`sw.js`, `icons/`), installable to the home screen, offline-capable, deployed
via Cloudflare Pages from `main` (build output directory: `src`).

It shares one schema and one Cloudflare KV namespace with the main repo —
two views of the same data. Schema changes land in both repos together
(see `CLAUDE.md`, Schema lockstep). The sync Worker lives in the main repo
at `sync/`.

## Docs

- `CLAUDE.md` — project constitution
- `DECISIONS.md` — decision log & parking lot
- `glass-ball-tracker.html` (main repo) — build tracker

*Built by Chad, for Joelle, co-designed by both.*
