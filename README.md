# NSpire Tea — Mobile Menu

A fast, searchable customer menu for NSpire Tea. 100% static, hosted free on GitHub Pages.

- **Live menu:** https://beardedinfosec.github.io/NSpire/

## How it works

| File | Purpose |
|---|---|
| `index.html` | The public menu customers see (via the QR code). Reads `menu.json`. |
| `menu.json` | The menu database — **customer-facing** drink info only (name, ingredients, tags, price). |
| `source/` | **Private** original staff build-sheets (PDF/PNG). Git-ignored — never published. |

Customers see **what flavors are in a drink**, not how it's made. The scoop-by-scoop staff recipes live only in `source/` on your computer and are never uploaded.

## Editing the menu

Edit `menu.json` directly and push to `main`. Changes go live in ~1 minute.

## The QR code

The QR code just needs to encode the live URL:

```
https://beardedinfosec.github.io/NSpire/
```

Generate one at any QR site (e.g. qr-code-generator.com), or ask and one can be added to the repo.

## Menu sections

Loaded Teas · Protein Shakes · Iced Coffees · Caffeine-Free · Mega Refreshers · Dirtea Sodas (Kids drinks are tagged within Loaded Teas). Specialty drinks (the old "S = Y") show a ★ badge and cost more.
