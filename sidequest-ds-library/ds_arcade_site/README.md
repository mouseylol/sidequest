# Sidequest

A minimal DS game library UI. The library view is intentionally just game tiles, with a small **Add games** control to select local `.nds`, `.srl`, or `.dsi` files. Selected filenames appear as cards for the current page session.

**Important:** this is currently a frontend prototype. It does not emulate games yet, and selected game files are not persisted after refreshing the page. The browser-compatible melonDS core still needs to be integrated and tested.

Run with a local HTTP server (rather than opening `index.html` via `file://`) when integrating the emulator.
