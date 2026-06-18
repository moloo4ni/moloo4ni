## moloo4ni

rust · figma · web · android

## about

vibe-coding tools and experiments in rust.  
ui/ux design in figma.  
web - html, css, ts, node.js, vite, svelte.  
env - arch linux · kitty · cargo

## github pages

**[bio](https://moloo4ni.github.io/bio)** — minimal bio card with skills & links

**[pathologiarium](https://moloo4ni.github.io/pathologiarium)** — lore-driven fictional disease wiki (35+ entries, search autocomplete)

## projects

**[cabbage](https://github.com/moloo4ni/cabbage)** — local-first markdown notes app (tauri v2 + rust + svelte 4, vite 6, codemirror 6, lucide/svelte, git2). stores notes as plain `.md` in a git vault — no proprietary database or cloud lock-in. backlinks, graph view, full-text search (ctrl+p), auto-save with git commits, note history with restore, vault persistence, one-click git sync, dark theme. MPL 2.0.

**[tendril](https://github.com/moloo4ni/tendril)** — scroll-driven wayland compositor in smithay + rust. dynamic multi-column layout (configurable count) with per-column vertical strip scrolling — no floating windows or stacking. nested compositor (winit), xdg-shell, xdg-decoration, popup surfaces. smooth animation (lerp scroll, persistent z-effect fade). ipc: json-rpc 2.0 over unix socket + `tendrilc` cli (all 7 methods). 5 workspaces, keyboard navigation (hjkl), z-effect reorder, toml config with auto hot-reload, column balancing, damage-aware rendering.

**[statusbar-fix-obsidian](https://github.com/moloo4ni/statusbar-fix-obsidian)** — magisk/ksu/apatch module fixing status bar height, qs offsets and lock screen layout on redmi note 14 pro 4g (obsidian) running lineageos gsi. dual rro overlays, notch killer, amoled burn-in protection, gsi conflict resolution.

**[fod-fix-obsidian](https://github.com/moloo4ni/fod-fix-obsidian)** — magisk/ksu/apatch module enabling under-display fingerprint sensor on redmi note 14 pro 4g (obsidian) with lineageos gsi. low-latency polling daemon, dynamic backlight boosting, phh gsi integration, persist calibration recovery.
