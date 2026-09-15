# Live Flight Tracker

A small, static wrapper around the live ADS-B Exchange globe. It keeps the map full-bleed while providing a lightweight, responsive header and attribution chrome.

## Open locally

Open `index.html` directly in a browser. For a local static server, from this directory run:

```bash
npx serve .
```

Then open the local URL shown by the command.

## Notes

- The embedded map loads from `https://globe.adsbexchange.com/` in an iframe.
- Some browsers, privacy settings, or extensions block third-party frames. If the iframe is blank, use **Open on ADS-B Exchange** in the header to open the live globe directly.
- The theme toggle changes this wrapper only; the embedded ADS-B Exchange page controls its own appearance.
- No API key, proxy, or backend is required.
