# Kanso Coffee — brand direction studies

Seven brand-direction landing-page studies for an artisan coffee brand; each is a
self-contained Design Compiler mock (`.dc.html`) that loads `support.js` and compiles
client-side.

| # | Direction | Ethos |
|---|-----------|-------|
| 01 | koel coffee co. (`Koel v2.dc.html`) | Warmth as craft. Scrapbook of taped polaroids, stickers, and the koel bird — mascot-led. |
| 02 | KANSO (`Kanso.dc.html`) | Omission as luxury. Japandi calm, one botanical line drawing, generous whitespace. |
| 03 | VESPER CO. (`Vesper.dc.html`) | Provenance as theatre. Warm & earthy apothecary framing, lot numbers, a roast ledger. |
| 04 | FORM. (`Form.dc.html`) | Precision as identity. Dark espresso, Swiss geometric, roast curves and agtron scores. |
| 05 | VOLT// (`Volt.dc.html`) | Energy with receipts. Cyberpunk, Gen Z, meme-literate copy backed by real macros. |
| 06 | CEMNT (`Cemnt.dc.html`) | Precision as brute force. Hard industrial, brutalist, batch tickets and PSI ratings. |
| 07 | SI SAV (`Sisav.dc.html`) | Heritage as ritual. Traditional Indian folk art, hand-drawn Madhubani line-art, jute. |

Directions are listed in gallery order (see `Index.dc.html`).

## Viewing locally

These must be served over HTTP (not opened via `file://`) because `support.js` compiles
the `<x-dc>` markup client-side:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000/Index.dc.html`.

## Note

Koel v2 hotlinks its photography from `images.unsplash.com` and loads GSAP but does not
call it (all its motion is hand-rolled CSS/rAF) — these would need addressing before any
production use.
