# Group contribution guide

This repository publishes the portfolio at its root as well as the portfolios in `members/`. To keep everyone's work separate:

1. Create a folder at `members/<github-username>/`, using your GitHub username in lowercase.
2. Copy the contents of `members/_template/` into your folder. Keep `_template/` as the shared starter; make changes only in your own folder.
3. Replace every bracketed placeholder and instructional comment with accurate information about yourself. Add only facts, links, and work you can verify. Remove sections you do not need.
4. Keep all files for your portfolio inside your own folder. Do not edit or move the root portfolio files (`index.html`, `styles.css`, `script.js`, or `public/`), or another contributor's folder.
5. Use relative paths for stylesheets, scripts, and other assets (for example, `styles.css` or `assets/photo.jpg`), not paths beginning with `/`. This keeps links working under a GitHub Pages project subpath.

Preview the site locally from the repository root with `python3 -m http.server 8000`, then visit `http://localhost:8000/members/<github-username>/`. The repository's Pages workflow uploads the repository root, so a portfolio will be available at `.../members/<github-username>/` on the published site without any workflow changes.

See [`members/_template/README.md`](members/_template/README.md) for the starter's file-by-file instructions.
