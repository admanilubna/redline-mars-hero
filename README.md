# Redline — Mars Trips Hero

A single-page, full-viewport three-step landing experience built with HTML, CSS, vanilla JavaScript, and Three.js r170.

## Run locally
Because the page uses JavaScript modules, serve this folder over HTTP rather than opening `index.html` directly:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Notes
- The page loads the four supplied image assets and Montserrat from their specified remote URLs.
- Three.js r170 is loaded from jsDelivr via an import map.
- An internet connection is required for the external assets and module.
- Interactions: scroll or use Escape to move between stages; drag the globe to rotate; click the globe, site timeline, Explore, or navigation dots to move through the experience.
