# LDP-Hackday
Content for the April 13 LDP Hackday

## GitHub Pages Deployment

The workflow [.github/workflows/github-pages.yml](.github/workflows/github-pages.yml) renders [quarto/presentation.qmd](quarto/presentation.qmd) with Pixi and deploys it on each push to `main`.

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
