# LDP-Hackday
Content for the April 13 LDP Hackday

## Deploy Presentation to GitHub Pages

The workflow [.github/workflows/github-pages.yml](.github/workflows/github-pages.yml) renders [quarto/presentation.qmd](quarto/presentation.qmd) with Pixi and deploys it on each push to `main`. In the repository **Settings → Pages**, set **Build and deployment** source to **GitHub Actions**. The site URL will be `https://<user>.github.io/LDP-Hackday/` (slides at `/`, i.e. `index.html`).

## Run the Code Locally

Install pixi for managing packages ([docs](https://pixi.prefix.dev/latest/installation/)):

```
curl -fsSL https://pixi.sh/install.sh | sh
```

Clone the repository and cd into the directory:

```
git clone https://github.com/tylere/LDP-Hackday.git
cd LDP-Hackday/
```

Install the necessary packages and preview the presentation:

```
pixi run quarto preview quarto/presentation.qmd
```
