# Adriano Bhagas — Portfolio

A lightweight, responsive portfolio site built with semantic HTML, CSS, and a small JavaScript navigation enhancement. The visual language uses a black-and-white editorial layout with a lime accent, inspired by minimalist infographic CVs.

## Local preview

No build step is required. From the repository root, run a local static server:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## GitHub Pages deployment

The workflow in `.github/workflows/deploy.yml` deploys the repository root to GitHub Pages whenever `main` is updated. In the repository settings, set **Pages → Source** to **GitHub Actions**. The workflow can also be started manually from the Actions tab.

## Source

Portfolio content is based on `public/assets/CV-01.pdf`, including the education, objective, experience, skills, projects, and contact details represented on the page.

## Group contributions

Each teammate should build their portfolio in `members/<github-username>/` and leave the root portfolio files unchanged. Start from the reusable [portfolio template](members/_template/README.md), and follow the [contribution guide](CONTRIBUTING.md) for setup, content, and GitHub Pages subpath requirements.
