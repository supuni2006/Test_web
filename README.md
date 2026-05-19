# Kngu — Flower Shop Homepage

A static, responsive homepage built for an internship coding exercise.

## Stack
- Plain HTML5 + handwritten CSS (no framework, no build step)
- Google Fonts: Cormorant Garamond (display) + Inter (body)
- Placeholder imagery from Unsplash

## Structure
```
.
├── index.html      # Single-page homepage
├── css/
│   └── styles.css  # All styles, organized by section
└── README.md
```

## Run locally
Just open `index.html` in a browser. No build, no dependencies.

```
open index.html
```

Or serve it with any static server:
```
python3 -m http.server 8000
```

## Notes
- Layout is responsive down to mobile (single-column at <560px).
- Semantic HTML (`<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`).
- Design tokens centralized as CSS custom properties at the top of `styles.css`.
- The newsletter form is hooked up with a tiny inline handler purely to demonstrate state — no backend.
