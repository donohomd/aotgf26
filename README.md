# aotgf26: Monteleone Art of the Guitar Festival 2026 (true black)

The attendee schedule for the **2026 John Monteleone "Art of the Guitar" Festival**
at The Jazz Loft, 275 Christian Avenue, Stony Brook, NY. Thursday–Saturday,
October 15–17, 2026.

**Live:** https://donohomd.github.io/aotgf26/

The site was built with [Rotapas](https://rotapas.com) and is a **true-black
(`#000000`) visual experiment**. It's the standard Rotapas attendee renderer
with its color tokens re-valued for a black page. Everything else (layout,
behavior and data) is the renderer's own.

The source, the build report and the Midnight original live in the Rotapas
repository, under `events/monteleone-2026/` (`experiments/true-black/` for this
version).

Schedule information is from [thejazzloft.org](https://thejazzloft.org/2026-monteleone-guitar-festival/).
It is unofficial; check with The Jazz Loft for tickets and changes.

## Files

| File | What it is |
|---|---|
| `index.html` | The page: the renderer with the black tokens |
| `schedule.json`, `version.json` | The compiled schedule and its version, which drives updates |
| `sw.js`, `manifest.webmanifest` | Offline support and Add to Home Screen |
| `.github/workflows/pages.yml` | Publishes the folder to GitHub Pages on every push |
