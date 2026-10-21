# Kanso Coffee — repo rules
Master rules load from the owner's user-level CLAUDE.md. This file adds rules and context for this repo only.

## Stakes & Status
- Paying users: no · Payments: no · User data: no (brand-direction mocks only) (recorded 2026-10-21, proposed — owner confirms)
- High-stakes paths: none.

## Rules
- DON'T commit secrets, API keys, store credentials or real customer data.
- DO keep each brand direction a self-contained `.dc.html` that loads `support.js`.
- DO list a new direction in the `README.md` table and in the gallery order in `Index.dc.html`.
- DO serve the mocks over HTTP, never `file://`, because `support.js` compiles the markup in the browser.
- DON'T treat these mocks as production-ready; hotlinked photography and unused scripts must be fixed first (see the README note).

## Context
- What: seven brand-direction landing-page studies for an artisan coffee brand.
- Stack: static Design Compiler mocks (`.dc.html`) with `support.js`; no build step.
- Licence: none stated.
