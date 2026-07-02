# Marius Cretu — Portfolio

A responsive single-page portfolio website for Marius Cretu. The site presents professional background, technical skills, featured projects, services, contact details, and a downloadable CV in a clean static web experience.

Built with vanilla HTML, CSS, and JavaScript, this project focuses on fast loading, simple deployment, responsive layout, and clear presentation without relying on a frontend framework.

## Purpose

This portfolio is designed to give recruiters, clients, and collaborators a quick overview of who I am, what I build, and how to contact me. It acts as both a personal landing page and a practical example of my ability to structure, style, and ship a polished static website.

## Features

- Responsive single-page layout for desktop, tablet, and mobile screens.
- Hero section with profile image, introduction, CV download, and contact actions.
- Skills and services sections to summarize technical capabilities.
- Featured projects section for highlighting selected work.
- Smooth scrolling navigation and mobile hamburger menu.
- Lightweight static structure that can be deployed on any static hosting platform.

## Tech stack

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Font Awesome

## Project structure

- `index.html` — main page with all sections and content.
- `styles.css` — styling for layout, typography, responsiveness, and hover states.
- `script.js` — navigation hamburger toggle, smooth scrolling, and navbar styling on scroll.
- `marius-photo.jpg` — profile image used in the hero section.
- `CV_MariusCretu.pdf` — downloadable CV linked from the hero buttons.

## Running locally

This is a static site with no build step required.

1. Clone or copy the repository files.
2. Open `index.html` directly in your browser.
3. Optionally, serve the folder with a static server:

```bash
python -m http.server 8000
```

or:

```bash
npx serve .
```

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

## Author

**Marius Cretu**

- Portfolio: https://cremarnic.github.io/Portfolio/
- LinkedIn: https://www.linkedin.com/in/marius14cretu
- GitHub: https://github.com/CreMarNic
