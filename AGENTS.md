# Repository Guidelines

## Project Structure & Module Organization
- `index.html` and `redesign-1.html` are the primary pages in this repo.
- `assets/images/` holds all local imagery referenced by the HTML.
- There is no build system or source directory; changes are made directly in the HTML and asset files.

## Build, Test, and Development Commands
- No build or test tooling is configured.
- To preview locally, open `index.html` or `redesign-1.html` in a browser.
- If you need a quick static server, run `python -m http.server` from the repo root and browse to `http://localhost:8000/`.

## Coding Style & Naming Conventions
- Keep files in plain HTML/CSS with Tailwind utility classes used inline.
- Use 2-space indentation in HTML blocks to match existing formatting.
- Prefer ASCII characters in edits and keep class lists consistent with existing ordering.
- Image paths should be relative, e.g., `assets/images/hero-image.png`.

## Testing Guidelines
- No automated tests are present.
- Validate changes by manually loading the HTML pages and checking layout on desktop and mobile widths.

## Commit & Pull Request Guidelines
- No commit message convention is defined in this repository; use clear, imperative summaries (e.g., "Update hero image layout").
- For PRs, include:
  - A short summary of changes.
  - Screenshots for any visual updates (desktop + mobile).
  - Links to relevant issues if applicable.

## Configuration & Assets
- Keep new assets under `assets/images/` and use descriptive, kebab-case filenames.
- Avoid external image URLs unless explicitly required; prefer local assets for stability.
