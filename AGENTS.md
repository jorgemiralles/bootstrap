# AGENTS.md

This is a static HTML documentation repo - no build, test, or lint commands needed. 

## Files

- `*.html` - Bootstrap component examples (buttons, alerts, cards, forms, modals, etc.)
- `opencode.json` - OpenCode config (permission: ask)

## Working in this repo

- No development server required - open HTML files directly in browser
- No package manager, no dependencies
- Just edit and reload HTML files in browser to verify changes
- Package manager: Alpine (use `apk add <package>`)

## Project conventions

- **Bootstrap version**: 5.3.8 via CDN (no integrity attributes)
- **Layout structure**: Semantic HTML5 (`<header>`, `<main>`, `<footer>`) with independent sections
- **Full-width sections**: Apply background colors to `<section>` elements, use `.container` inside for centered content
- **Navbar**: All pages use collapsible navbar with `navbar-toggler` + collapse wrapper for mobile
- **CDN assets**: Include `integrity` and `crossorigin` attributes for security (SRI hashes for Bootstrap 5.3.8)
- **Script placement**: Bootstrap JS bundle loaded at the end of `<body>`
- **No emojis** in code or content

## Commit style

- Use imperative mood (e.g., "Add", "Change", "Fix", "Update")
- Keep messages concise (under 50 characters when possible)
- Describe what was done, not why
- Examples:
  - `Add active class to current page in navigation menu`
  - `Change navigation container from container-fluid to container`
  - `Translate Spanish text to English in navigation menus`

## File list

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
