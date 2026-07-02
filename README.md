# Marius Cretu - Java Full Stack Developer Portfolio

A responsive single-page portfolio website for Marius Cretu, focused on Java full stack developer opportunities. The site presents professional background, technical skills, selected projects, contact details, and a downloadable CV in a clean static web experience.

Built with vanilla HTML, CSS, and JavaScript, this project focuses on fast loading, simple deployment, responsive layout, and clear recruiter-facing presentation without relying on a frontend framework. The design uses a dark professional layout with orange call-to-action styling, centered section headers, responsive project cards, and direct links to GitHub and LinkedIn.

## Purpose

This portfolio is designed to give recruiters, clients, and collaborators a quick overview of my Java full stack profile. It highlights Spring Boot, React, REST APIs, authentication, databases, deployment, and project ownership across the stack through live projects and source-code links.

## Live site

https://cremarnic.github.io/Portfolio/

## Features

- Responsive single-page layout for desktop, tablet, and mobile screens.
- Hero section with profile image, Java full stack positioning, CV download, and professional links.
- About section describing full stack delivery and project ownership.
- Skills section covering backend, data, frontend, and delivery.
- Projects section with live demos, GitHub links, project status, proof points, and technologies used.
- Focus section describing where I can contribute on a Java full stack team.
- Contact section with email, phone, location, GitHub, and LinkedIn.
- Smooth scrolling navigation and mobile hamburger menu.
- Lightweight static structure that can be deployed on any static hosting platform.

## Tech stack

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Font Awesome

## Project structure

- `index.html` - main page with all sections and content.
- `styles.css` - styling for layout, typography, responsiveness, and hover states.
- `script.js` - navigation hamburger toggle, smooth scrolling, and navbar styling on scroll.
- `marius-photo.jpg` - profile image used in the hero section.
- `CV - Marius Cretu.pdf` - downloadable CV linked from the hero buttons.

## Running locally

This is a static site with no build step required.

1. Clone or copy the repository files.
2. Open `index.html` directly in your browser.
3. For a local preview that behaves more like GitHub Pages, serve the folder with a static server:

```bash
npx serve -l 8000 .
```

Then open `http://localhost:8000`.

## Customization

- **Content:** Update text and links directly in `index.html` (hero intro, about, skills, projects, focus, contact details).
- **Images:** Replace `marius-photo.jpg` and project thumbnails as needed; adjust image paths in the markup.
- **Styling:** Tweak colors, spacing, gradients, cards, and layouts in `styles.css`. Media queries at the bottom handle mobile navigation and responsive grids.
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
