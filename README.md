# Lectures

This repository contains course materials published separately from the main website.

Current course:

- `edo`

## Local workflow

1. Open the project in RStudio or use Quarto from the terminal.
2. Preview locally:

```bash
quarto preview
```

If you prefer RStudio, render:

- `lectures/index.qmd`
- `lectures/edo/index.qmd`

3. Render the site:

```bash
quarto render
```

This creates the `docs/` folder, which is the folder GitHub Pages should publish.

## GitHub Pages

1. Create a GitHub repository named `lectures`.
2. Push this repository to GitHub.
3. In GitHub, open `Settings > Pages`.
4. Choose `Deploy from a branch`.
5. Select branch `main` and folder `/docs`.

The site is configured to publish at `https://mdazatorres.github.io/lectures/`.
