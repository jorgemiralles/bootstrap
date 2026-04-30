---
name: bootstrap-guidelines
description: Guidelines for working with Bootstrap 5.3.8 in the static HTML documentation repo, including project conventions, file structure, and coding standards.
license: MIT
compatibility: opencode
metadata:
  project: bootstrap-docs
  audience: developers
---

## What I do
- Provide project-specific conventions for Bootstrap 5.3.8 usage
- Explain file structure and purpose of each HTML component file
- Detail CDN, layout, navbar, and script placement rules
- Outline repo workflow (no build/test/lint, edit and reload browser)

## When to use me
Use this skill when modifying or creating Bootstrap component HTML files in this repo. Ask clarifying questions if unsure about project conventions.

## Project Conventions
- **Bootstrap version**: 5.3.8 via CDN
- **Layout**: Semantic HTML5 (`<header>`, `<main>`, `<footer>`) with independent sections. Full-width sections use background colors on `<section>`, `.container` inside for centered content
- **Navbar**: All pages use collapsible navbar with `navbar-toggler` + collapse wrapper for mobile
- **CDN assets**: Include `integrity` and `crossorigin` attributes for security (SRI hashes for Bootstrap 5.3.8)
- **Script placement**: Bootstrap JS bundle loaded at end of `<body>`
- **No emojis** in code or content

## Repo Workflow
- No build, test, or lint commands needed
- Open HTML files directly in browser to verify changes
- No package manager or dependencies
- System packages: Alpine (`apk add <package>`)

## File List
| File | Description |
|---|---|
| `index.html` | Landing page with hero section, 6-component card grid, footer |
| `containers.html` | Container examples |
| `grids.html` | Grid system examples (offsets, nesting, ordering, alignment, mixed breakpoints) |
| `colorsandtext.html` | Color and text utilities |
| `tables.html` | Table styling examples |
| `alerts.html` | Alert components |
| `buttons.html` | Button components |
| `cards.html` | Card components |
| `navbars.html` | Navigation components |
| `modals.html` | Modal dialogs |
| `forms.html` | Form components |
