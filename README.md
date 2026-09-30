# The Gate of Nyandor — Nyandor Protocol

Single-page direct-response prototype for **The Gate of Nyandor** book series.

## Local preview

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Deployment

Static site. A GitHub Pages workflow is included in `.github/workflows/pages.yml`.

## Amazon destinations

| Link | ASIN |
|---|---|
| Book One paperback | `B0G5Z7HNQK` |
| Book One Kindle | `B0G8DDNS3Q` |
| Book Two paperback | `B0GDM8QB5H` |

Every purchase link carries a `data-cta` attribute (e.g. `hero-dose1-paperback`) so analytics or Amazon Attribution tags can be wired per placement. Prices on the page are hard-coded list prices; update them if Amazon's change.

## Assets

- `assets/*-360.webp` / `*-720.webp`: covers, generated from the print-cover originals
- `assets/voyd-pair-*.webp`: the conjoined covers
- `assets/faelspire-map-*.webp`: map of Faelspire
- `assets/og-protocol.jpg`: 1200×630 social share image
- `assets/fonts/`: self-hosted Anton and EB Garamond (SIL Open Font License)

## Still to do

- Amazon Attribution (or other analytics) wired to the `data-cta` hooks
- Book Two Kindle link once it's listed
- Recorded VSL, if wanted; the text briefing stands in for it
