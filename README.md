# Marius Cretu — Portfolio

A single-page portfolio site for Marius Cretu showcasing skills, featured projects, services, and contact info. Built with vanilla HTML, CSS, and a small JavaScript helper for navigation interactions.

## Project structure

- `index.html` — main page with all sections and content.
- `styles.css` — styling for layout, typography, responsiveness, and hover states.
- `script.js` — navigation hamburger toggle, smooth scrolling, and navbar styling on scroll.
- `marius-photo.jpg` — profile image used in the hero section.
- `CV_MariusCretu.pdf` — downloadable CV linked from the hero buttons.

## Running locally

This is a static site—no build step required.

1) Clone or copy the repository files.  
2) Open `index.html` in your browser, or serve the folder with any static server (examples: `python -m http.server 8000` or `npx serve .`).

## Customization

- **Content:** Update text and links directly in `index.html` (hero intro, projects, services, contact details).
- **Images:** Replace `marius-photo.jpg` and project thumbnails as needed; adjust image paths in the markup.
- **Styling:** Tweak colors, spacing, and layouts in `styles.css`. Media queries at the bottom handle mobile navigation and responsive grids.
- **Behavior:** Modify `script.js` if you want different scroll behavior or menu animations.

## External dependencies

- Google Fonts: Inter (loaded via `<link>` in `index.html`)
- Font Awesome 6 (CDN) for icons

## Deployment

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages, etc.). Deploy the root folder and ensure all assets stay in the same relative paths.
