# P&D Truck Rental

A clean, fast, static rebuild of the P&D Truck Rental website — truck rental
for parcel delivery. Shelved step vans (P 700, P 900, P 1000) for logistics
professionals serving Amazon, DHL, FedEx, UPS & USPS.

## Pages
- `index.html` — Home (hero slider, vehicles, app download, affiliates, contact)
- `getting-started.html` — How it works + FAQ
- `about.html` — Company overview & why P&D
- `vehicles.html` — Available vehicles
- `gallery.html` — Truck image gallery
- `contact.html` — Contact info + form

## Structure
- `css/styles.css` — all styles (brand purple, Sofia Sans Extra Condensed + Roboto)
- `js/main.js` — mobile nav, hero slider, login/locations modal, contact form
- `assets/` — inline SVG illustrations (no external image dependencies)

## What was fixed vs. the original
- Replaced the heavy WordPress/Elementor stack (many plugins, jQuery, multiple
  carousels) with a dependency-free static site for much faster loads.
- Fixed broken footer links that pointed to `#`.
- Removed a leftover debug modal.
- Corrected copy/grammar (e.g. "become an affiliate").
- Added an accessible nav toggle, keyboard-dismissible modal, real `tel:`/`mailto:`
  links, semantic headings, and responsive layouts.

## Develop locally
```bash
python3 -m http.server 8099
# open http://localhost:8099
```
