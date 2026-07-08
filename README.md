# Healthcare Website — Willowbrook Family Clinic

A single-page, responsive healthcare clinic landing page. Pure HTML, CSS, and vanilla
JavaScript in one `index.html` file — no framework, no build step, no dependencies.

**Live site:** https://christabelletan21.github.io/healthcare-website/

## Preview

![Screenshot of the Willowbrook Family Clinic landing page](screenshot.png)

## Features

- Sticky, responsive navbar with mobile hamburger menu and smooth-scroll anchor links
- Hero section with gradient background, call-to-action buttons, and a trust-indicator strip
- Services grid, patient testimonials with star ratings and initials avatars
- Appointment enquiry form with client-side validation (required fields, email format,
  phone format), inline error messages, and a success confirmation — no backend required
  (submission is logged to the browser console, with a marked spot to wire up a real API)
- Footer with contact details, quick links, social placeholders, and an auto-updating
  copyright year
- Semantic HTML5, labelled form fields, keyboard-friendly navigation, fade-in-on-scroll
  animations

## Tech Stack

HTML5 · CSS3 · Vanilla JavaScript — no frameworks, no build tooling.

## Running Locally

Just open `index.html` in a browser. There is nothing to install or build.

## Deployment

Deployed automatically to GitHub Pages via GitHub Actions
(`.github/workflows/pages.yml`) on every push to `main`.

## Project Structure

```
healthcare-website/
├── index.html      # entire site: markup, styles, and script
├── screenshot.png  # preview image used in this README
└── .github/workflows/pages.yml
```

## License

MIT
