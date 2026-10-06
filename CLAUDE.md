# Feelings Field Guide

Chris's personal PWA for naming what he feels – twelve feeling families,
mild→intense ladders, deep dives with what each feeling asks for. The README
carries the why; read it first. Migrated from a Cowork session 2026-10-06
with git history intact.

## Working rules

- This is a personal wellbeing tool, not a product. No analytics, no
  accounts, no backend – it stays a static offline-capable PWA unless Chris
  says otherwise. Content changes matter more than features.
- The feeling words and their meanings are Chris's curation (with his men's
  group in the lineage) – propose wording changes, never silently rewrite
  emotional content.
- Plain static stack: index.html + sw.js + manifest. Keep it dependency-free;
  no build step unless the project genuinely outgrows one.
- Chris approves every commit. Deployed on GitHub Pages from the `main`
  branch root at https://chgiersch.github.io/feelings/ – GitFlow from here:
  features off `dev`, releases merge to `main`.
- Any change to index.html must bump `VERSION` in sw.js, or installed
  phones keep serving the old copy from the service worker cache.
- HANDOFF.md lives in gitignored `_working/`, not the root – it is session
  state, not something the public repo should carry.

## Session protocol

Open by reading HANDOFF.md; close with /wrap. Session titles: `Feelings – <context>`.
