# Rasmehina

A modern, responsive portfolio website for **Rasmehina**, a professional henna design artist based in Gothenburg, Sweden.

> Personal website notice: This is a personal website project and is not open for public editing or external contributions.

## Overview

This project is a single-page website built with HTML, CSS, and vanilla JavaScript. It showcases services, portfolio work, testimonials, and a booking/contact section for clients.

## Features

- Hero section with autoplay image slider and animated particles
- Service cards for bridal, party, Arabic, jagua/white henna, baby shower, and workshops
- Filterable gallery with lightbox preview
- Testimonial carousel
- Booking form with basic client-side UX (loading/success states)
- Smooth scrolling navigation, animated counters, and back-to-top button
- Fully responsive layout with mobile navigation

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- [AOS](https://michalsnik.github.io/aos/) for scroll animations
- [Swiper](https://swiperjs.com/) for sliders
- [GLightbox](https://biati-digital.github.io/glightbox/) for gallery lightbox
- [Font Awesome](https://fontawesome.com/) for icons
- [live-server](https://www.npmjs.com/package/live-server) for local development

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 16+ (or any recent LTS)
- npm

### Install and Run

```bash
npm install
npm start
```

The app runs at:

- `http://localhost:3000`

## Available Scripts

- `npm start` - Starts local dev server on port `3000`
- `npm test` - Placeholder script (currently not configured)

## Project Structure

```text
rasmehina/
├── index.html
├── index.js
├── package.json
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── main.js
    └── images/
        └── ...
```

## Notes

- Main front-end logic lives in `assets/js/main.js`.
- The booking form currently simulates submission on the front end; no backend/API integration is included yet.
- Most third-party UI libraries are loaded via CDN in `index.html`.
- This repository is maintained privately by the owner and is not intended for community edits.

## License

This project is private (`"private": true` in `package.json`). Add a license section here if you plan to publish it publicly.
