# Portfolio starter template

This folder is a reusable, static portfolio starter. It uses plain HTML, CSS, and JavaScript and has no build step or external assets.

## Make your portfolio

1. From the repository root, copy this folder to `members/<github-username>/` (use your lowercase GitHub username). For example:

   ```bash
   cp -R members/_template members/<github-username>
   ```

2. Edit the copy, not `members/_template/`. Replace every bracketed placeholder and HTML instruction comment in `index.html` with your own accurate details. Update the page title, description, initials, section labels, and footer too. Remove any sections that do not apply.
3. Add optional files, such as a CV or images, inside your own folder. Reference them with relative paths such as `assets/cv.pdf`; do not use root-relative paths such as `/assets/cv.pdf`.
4. Preview from the repository root:

   ```bash
   python3 -m http.server 8000
   ```

   Open `http://localhost:8000/members/<github-username>/` in a browser. Use your actual folder name in place of `<github-username>`.

## Files

- `index.html` — semantic page structure and clearly marked content placeholders.
- `styles.css` — responsive visual styling, focus indicators, and reduced-motion support.
- `script.js` — small accessible mobile navigation toggle.

The site's stylesheet and script are linked relative to `index.html`. Keep that pattern for any assets you add so the portfolio works when published below the repository's GitHub Pages URL.
