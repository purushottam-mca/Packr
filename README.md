# 🎒 Packr

A minimal, offline-first packing checklist PWA. Single HTML file, no dependencies, no build step.

**Live:** https://purushottam-mca.github.io/Packr/

## Features

- Multiple event checklists (trips, flights, etc.) in tabs
- 3-tap item states: checked → N/A → unchecked
- Custom emoji + names for items and sections
- Collapsible sections with progress counters
- Export the finalized list as TXT or PNG (event name + date header; all items with statuses, or selected only)
- Light/dark mode
- 100% client-side, data saved in `localStorage`
- Installable PWA, works offline via service worker

## Run

Use the live URL above, or run locally:

```bash
git clone https://github.com/purushottam-mca/Packr.git
cd Packr
open index.html   # or just double-click it
```

## Install as app

Serve over HTTPS (or localhost) and use your browser's "Install app" option.

## License

[MIT](LICENSE)

