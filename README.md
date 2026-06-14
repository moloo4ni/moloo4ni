## moloo4ni

rust · figma · web · android

## about

vibe-coding tools and experiments in rust.  
ui/ux design in figma.  
web - html, css, ts, node.js, vite, svelte.  
env - arch linux · vscodium · kitty · cargo

## projects

**[cabbage](https://github.com/moloo4ni/cabbage)** — local-first markdown notes app (tauri v2 + rust + svelte 4).  
stores notes as plain `.md` files in a git vault — no proprietary database or cloud lock-in.  
license: MPL 2.0. ci: cargo check + clippy + svelte-check.

stack: tauri 2, svelte 4, typescript 5, vite 6, codemirror 6, git2 0.21 (vendored libgit2), lucide-svelte, d3-force.

features:
- codemirror 6 editor with wiki-link autocomplete
- backlinks panel with incremental index
- note history with per-file version restore
- force-directed graph view (click to navigate)
- full-text search (ctrl+p / cmd+p)
- git sync via native libgit2 (no system git dependency)
- dark theme (github dark palette, persisted, auto-detect)
- vault auto-restore on startup

status: all 16 initial issues closed. svelte 5 migration deferred (milestone created, not started).

**[statusbar-fix-obsidian](https://github.com/moloo4ni/statusbar-fix-obsidian)** — magisk/ksu/apatch module fixing status bar height, qs offsets and lock screen layout on redmi note 14 pro 4g (obsidian) running lineageos gsi. dual rro overlays, notch killer, amoled burn-in protection, gsi conflict resolution.

**[fod-fix-obsidian](https://github.com/moloo4ni/fod-fix-obsidian)** — magisk/ksu/apatch module enabling under-display fingerprint sensor on redmi note 14 pro 4g (obsidian) with lineageos gsi. low-latency polling daemon, dynamic backlight boosting, phh gsi integration, persist calibration recovery.

**[moloo4ni.github.io](https://github.com/moloo4ni/moloo4ni.github.io)** — personal site hosting pathologiarium (lore-driven wiki) and a bio card.
