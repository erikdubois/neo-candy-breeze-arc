# CLAUDE.md — neo-candy-breeze-arc

## Project overview

Standalone repo for the **neo-candy-breeze-arc** folder-icon theme — the same folder set as
`erikdubois/surfn-breeze-arc` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-breeze-arc/` — folders only. Packaged as `neo-candy-breeze-arc-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-breeze-arc/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
