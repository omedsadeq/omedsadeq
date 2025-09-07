BioZheen Site Documentation

Overview

- This documentation covers all public-facing pages, reusable UI sections, CSS classes, and client-side scripts found in the repository.
- Tech stack: Static HTML, Bootstrap 4.3.1, custom CSS (`css/style.css`), optional Google Maps script on `contact.html`.

Pages

- Home: `index.html`
- About: `about.html`
- Services: `service.html`
- Doctors: `doctor.html`
- Contact: `contact.html`

Sections and Components

- Header bar: top contact strip used across pages
- Navbar: Bootstrap navbar with brand logo and links
- Middle content blocks: `.middle` section containers
- Bottom/features list: only on `index.html`
- Appointment form: `index.html` and `service.html`
- Doctor cards: `.doctor-profile` in `doctor.html`
- Footer: shared footer across pages

Styles

- Global typography and layout in `css/style.css`
- Component-specific classes documented in `components.md`

Scripts

- Bootstrap JS + jQuery + Popper loaded from CDNs
- Google Maps initialization on `contact.html` (`initMap`)

Quick Start

1) Open `index.html` in a browser (no build needed)
2) Ensure `css/style.css` and images are in the expected folders (`css/`, `img/`)
3) For maps, set a valid Google Maps API key in `contact.html`

Reference

- See `pages.md` for page-specific docs
- See `components.md` for reusable sections
- See `styles.md` for CSS class reference
- See `scripts.md` for client-side functions and usage

