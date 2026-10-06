# OSINT Graph Workbench - PWA
Offline profiling investigator like Sintelix / Flowsint / LinkScope.

## Install via GitHub Pages
1. Create new public repo (e.g. `osint-workbench`)
2. Upload all files in this folder to repo root
3. Go to Settings > Pages > Source: Deploy from branch `main` / root
4. Wait 1 min, open `https://YOURUSERNAME.github.io/osint-workbench/`
5. Chrome/Edge will show Install icon in address bar -> Install

100% offline, stays on device, PWA installable.
- `index.html` = whole app
- `manifest.json` + `sw.js` = PWA plumbing
- `icons/` = app icons
- No build step needed.

### Features
- Graph investigation, entity palette, OSINT link generators
- Import/export JSON/CSV/PDF
- Autosaves to localStorage
