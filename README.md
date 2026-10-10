# scottmacrae

Personal website for Scott MacRae — fashion retail sourcing, buying, and brand development consultant.

## Overview

A lightweight, fully static site (no build step, no JavaScript, no dependencies):

- `index.html` — all page content
- `styles.css` — responsive styling with light/dark mode support

## Editing content

Open `index.html` and edit the relevant section directly:

| Content | Where |
|---|---|
| Intro / hero | `<section class="hero">` |
| About | `<section id="about">` |
| Key achievements | `<section id="achievements">` |
| Projects | `<section id="projects">` |
| Contact | `<section id="contact">` |

To add a project card, copy an existing `<li>` inside `<ul class="cards">` and update the `<h3>`, `<p class="role">`, and description.

## Accessibility

Built to W3C WCAG 2.1 AA and W3C HTML5 standards:

- Semantic HTML5 landmarks (`header`, `nav`, `main`, `section`, `footer`)
- Skip-to-content link and visible focus states
- Responsive layout with `prefers-reduced-motion` and dark-mode support
- English language declared (`lang="en"`); content is locale-neutral for an international audience

## Local preview

Open `index.html` directly in a browser, or:

```sh
python3 -m http.server 8000
```

then visit <http://localhost:8000>.
