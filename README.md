# Site Builder AI

A polished static landing page for a **Multi-Agent Team for Business Website Designing**.

## Live Demo

Once GitHub Pages is enabled, the website will be available at:

`https://unboxd-cloud.github.io/site-builder/`

## What This Project Does

This project presents a business website design service powered by a specialist multi-agent delivery team. The landing page explains the service, agent roles, web design offerings, technology stack, process, FAQs, and contact form UI.

## Multi-Agent Team

- **Business Strategist Agent**: Clarifies goals, audience, positioning, pages, and calls to action.
- **Brand & UI Agent**: Designs clean layouts, readable typography, balanced colors, and brand-focused visuals.
- **Copywriting Agent**: Converts business services and benefits into concise website copy.
- **Frontend Developer Agent**: Builds responsive HTML, CSS, and lightweight JavaScript.
- **SEO & Performance Agent**: Optimizes metadata, structure, page speed, and content hierarchy.
- **QA & Launch Agent**: Checks responsiveness, links, browser support, accessibility basics, and deployment readiness.

## Features

- Modern responsive landing page
- Hero section with clear CTA
- Multi-agent team showcase
- Services and why-choose-us sections
- Tools and technologies section
- Web design process section
- FAQ accordion
- Static contact form UI
- SEO metadata and Open Graph tags
- GitHub Pages deployment workflow

## Local Preview

Because this is a plain static website, you can open `index.html` directly in a browser.

Recommended local server:

```bash
python3 -m http.server 8080
```

Then visit:

```text
http://localhost:8080
```

## GitHub Pages Deployment

This repository includes `.github/workflows/pages.yml` for GitHub Pages deployment.

To enable Pages:

1. Open the repository settings on GitHub.
2. Go to **Pages**.
3. Set the source to **GitHub Actions**.
4. Push to `main` or run the workflow manually.

## Project Structure

```text
.
├── index.html
├── styles.css
├── script.js
├── .nojekyll
└── .github/workflows/pages.yml
```

## Notes

The contact form is currently static and ready to connect to a backend, CRM, email service, or form provider.
