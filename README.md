# Nandigiri Campus · Maintenance Stock Register

A single-page web app for the Nandigiri Campus maintenance department to track
equipment (bulbs, fans, tools, etc.) across every building, floor, and room —
with live roll-up totals at every level.

## Features
- Collapsible tree: Campus → Institute/Hostel → Floors → Rooms → Items
- Add, rename, recolor, or delete any node in one click
- Per-item counts: Working, Damaged, Repaired, New, Lost
- Automatic totals roll up from item → room → floor → building
- Expand all / Collapse all
- Light and dark theme
- No installation, no backend — runs entirely in the browser

## Usage
Open `index.html` in any modern browser (Chrome/Edge recommended), or visit
the [live GitHub Pages link](#) once enabled (see below).

Data is saved in your browser's local storage, so it stays on the device
you're using and isn't shared between devices yet.

## Enabling GitHub Pages (free hosting)
1. Go to the repo's **Settings** tab
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main`, folder: `/ (root)` → **Save**
5. Your live link appears at the top after a minute or two, in the form
   `https://<username>.github.io/nandigiri-maintenance-stock/`

## Tech
Plain HTML/CSS/JavaScript — no frameworks, no build step, no dependencies.

## Roadmap
- Shared cloud storage so the whole team sees the same data
- CSV/Excel export
- Search
