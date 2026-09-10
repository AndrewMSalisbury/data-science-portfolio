# Portfolio Website

Personal data science portfolio for Andrew Salisbury. Plain HTML/CSS/JS, no
build step.

## Running locally

Just open `index.html` in a browser — no server required.

## Structure

- `index.html` — home page (about, skills, projects, contact)
- `projects/` — one case-study page per project
- `css/style.css` — shared styles
- `js/main.js` — small page scripts
- `assets/img/` — images
- `assets/resume/` — resume PDF

## Updating content

- Bio: edit the paragraph in the `#about` section of `index.html`.
- Skills: edit the `<ul class="skills">` list in `index.html`.
- Adding a project: add a `.project-card` block to `index.html` and a new
  page under `projects/`, following the pattern of `projects/coach-valuation.html`.
