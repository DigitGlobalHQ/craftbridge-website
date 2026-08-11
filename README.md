# CraftBridge — Website

Landing page for CraftBridge: connecting authentic Indian artisans with global buyers
through AI-powered sourcing — discovery, procurement, quality control, catalog creation
and international commerce on one connected platform.

## Contents

| Path | Description |
| --- | --- |
| `index.html` | The complete site — markup, styles and scripts in one self-contained file |
| `assets/` | Images: logo, bridge, box, cart, globe, magnifier |

## Viewing it locally

No build step and no dependencies. Either open `index.html` directly in a browser, or
serve the folder so paths resolve exactly as they do in production:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000

## Notes

- Fonts (Instrument Serif, Outfit) load from Google Fonts, so a first paint needs a network connection.
- All asset paths are relative, so the site works from any subdirectory or static host.
