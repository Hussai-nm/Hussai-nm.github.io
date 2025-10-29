# Portfolio (Clean)

Structure:
- index.html
- about.html
- projects.html
- contact.html
- assets/
  - css/style.css
  - img/ (Du.jpeg, better.jpeg, focus.jpeg, imamali.jpeg, me.jpeg, najaf.jpeg)

What changed:
- Removed `.git` and `.DS_Store`.
- Consolidated CSS to `assets/css/style.css` (unused `contact.css` removed).
- Moved images into `assets/img/` and updated `<img src>` and CSS `url(...)` paths.
- Set `index.html` as the home page (was `new_portfolio.html`); nav links updated.

Where to edit:
- Global styles: `assets/css/style.css`
- Home (hero/landing): `index.html`
- About: `about.html`
- Projects: `projects.html`
- Contact: `contact.html`
- Images: place new files in `assets/img/` and reference as `./assets/img/yourfile.ext`

Deploy:
- If using GitHub Pages with `/docs`, move all files in `portfolio_clean` into your repo’s `docs/` directory (or set Pages root to `/root` and keep as-is).
