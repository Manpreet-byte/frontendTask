# Frontend Test

A static frontend implementation built with plain HTML, CSS, and a small inline JavaScript carousel.

## Overview

This project contains a landing-style product page with:

- A full-width hero image carousel
- Previous and next carousel controls
- Carousel dot indicators
- Hero call-to-action buttons
- A responsive product card section

## Project Structure

```text
.
├── index.html
├── styles.css
├── image.png
└── image.jpg
```

- `index.html` contains the page markup and carousel behavior.
- `styles.css` contains the layout, hero, carousel, and product card styling.
- `image.png` is used by the hero carousel.
- `image.jpg` is used by the product cards.

## Getting Started

No build step or package installation is required.

Open `index.html` directly in a browser, or run a local static server from the project directory:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Notes

- Keep `image.png` and `image.jpg` in the project root unless the paths in `index.html` and `styles.css` are updated.
- The carousel auto-advances every 5 seconds and can also be controlled with the arrow buttons.
