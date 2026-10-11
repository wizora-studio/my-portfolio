# Zaiqa Restaurant

Hand built restaurant website demos in vanilla HTML, CSS and JavaScript.
No frameworks, no build step. The main demo is **Zaiqa Restaurant**, a fictional
Pakistani restaurant site with a full multi page layout: home, menu, about,
gallery, reviews, FAQ and contact.

## Demos in this repo

| Folder | What it is |
| --- | --- |
| `/` (root) | The full Zaiqa Restaurant site |
| `/ZAIQA` | Alternate build of the Zaiqa site |
| `/restaurant` | Alternate build of the Zaiqa site |
| `modern_demo.html` | NEXUS, a modern trading interface concept page |

## Pages

- `index.html` — Home with hero, featured dishes and loader screen
- `menu.html` — Full menu (biryani, karahi, kebabs, naan, samosas, lassi)
- `about.html` — About the restaurant
- `gallery.html` — Food gallery
- `reviews.html` — Customer reviews
- `faq.html` — Frequently asked questions
- `contact.html` — Contact and location

## Features

- Fully responsive with a mobile hamburger menu
- Animated loading screen
- Lazy loaded images and preconnected fonts for fast first paint
- Accessibility: ARIA labels, visible focus states, semantic HTML
- SEO basics: meta descriptions, semantic structure, theme color
- Outfit typeface from Google Fonts

## How to view

No install needed. Open `index.html` in any modern browser:

```bash
# from the repo root
open index.html        # macOS
xdg-open index.html    # Linux
```

Make sure the `images/` folder sits next to `index.html` so the food photos load.

## Project structure

```text
├── index.html            # Home
├── menu.html             # Menu
├── about.html            # About
├── gallery.html          # Gallery
├── reviews.html          # Reviews
├── faq.html              # FAQ
├── contact.html          # Contact
├── modern_demo.html      # NEXUS trading UI concept
├── css/
│   ├── styles.css
│   └── modern_demo.css
├── js/
│   └── script.js
├── images/               # Food photography
├── ZAIQA/                # Alternate site build
└── restaurant/           # Alternate site build
```

## Tech

HTML5, CSS3, vanilla JavaScript. Images are local PNGs.

## Note

Zaiqa Restaurant is a fictional brand created for this demo. Built by
[wizora-studio](https://github.com/wizora-studio).
