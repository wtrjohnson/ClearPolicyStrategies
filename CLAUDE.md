# Clear Policy Strategies — Project Memory

## Project Overview
Website design and development for **Clear Policy Strategies**, a policy consulting firm. Current phase: evaluating two HTML design proposals before moving to final build.

## Files
| File | Purpose |
|---|---|
| `proposal-a.html` | **Selected design** — dark navy hero, EB Garamond + Inter fonts, gold accent |
| `Logo-nav.png` | Logo optimized for nav bar use |
| `Logo-traced.png` | SVG-style traced logo |
| `Logo.jpeg` / `Logo.ai` | Full logo assets |
| `Headshot1.jpeg` / `Headshot2.jpeg` | Team headshots |

## Design Tokens (shared across both proposals)
```
--navy: #1B3A6B
--navy-dark: #0F2447
--red: #C8102E
--white: #FFFFFF
--off-white: ~#F7F6F3
```

## Conventions
- Pure HTML/CSS — no frameworks, no build tools
- All styles inline in `<style>` block within each file
- Google Fonts via CDN
- Images referenced by filename (same directory)
- Smooth scroll via `html { scroll-behavior: smooth; }`

## Known TODOs
- [x] Client selected Proposal A (2026-04-23)
- [ ] Finalize copy / team bios
- [ ] Mobile responsiveness audit
- [ ] Final asset optimization

## Load on demand
- `@docs/progress.md` — session-by-session work log
- `@docs/session_summary.md` — compact summaries for context reload
