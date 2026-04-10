# LDP-Hackday
Content for the April 13 LDP Hackday

## GitHub Pages

The workflow [.github/workflows/github-pages.yml](.github/workflows/github-pages.yml) renders [quarto/presentation.qmd](quarto/presentation.qmd) with Pixi and deploys it on each push to `main`. In the repository **Settings → Pages**, set **Build and deployment** source to **GitHub Actions**. The site URL will be `https://<user>.github.io/LDP-Hackday/` (slides at `/`, i.e. `index.html`).
