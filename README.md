# Cambridge Room Planner

An interactive floor plan with draggable furniture, free rotation, size adjustments, and undo.

## Files

- `index.html` — complete, standalone website, including CSS and JavaScript. No installation or build step required.
- `source/room-planner.html` — readable original planner fragment, included as an editable reference. Changes to this reference do not automatically update `index.html`.
- `.nojekyll` — keeps GitHub Pages serving the files as a plain static site.

## Run locally

Open `index.html` in a browser, or run `python3 -m http.server 8000` in this directory and open http://localhost:8000.

## Publish with GitHub Pages

Upload this folder's contents to a GitHub repository. Configure GitHub Pages to deploy from your chosen branch and the repository root. The entry point is `index.html`.

No API keys, server, database, or package installation is required. The Site hosting configuration and credentials are not needed for GitHub Pages and are not included.

## Use

Drag furniture to move it. Select a piece and use the round rotation handle, angle slider, or 45-degree buttons to rotate it. The proportions panel changes its size. Undo reverses edits. Closet and furniture overlaps are flagged but allowed.

Room and furniture sizes are approximate sketch units, not measured dimensions. Each visitor edits their own temporary layout; changes are not saved after reloading or synchronized with others.
