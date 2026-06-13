# Elena Ballante personal website

This is a Quarto website configured for GitHub Pages at:

https://eballante.github.io

## Local preview

Install Quarto, then run from this folder:

```bash
quarto preview
```

## Render

```bash
quarto render
```

The rendered site will be created in the `docs/` folder, as configured in `_quarto.yml`.

## Publish on GitHub Pages

Create a GitHub repository named exactly:

```text
eballante.github.io
```

Then run:

```bash
git init
git add .
git commit -m "Initial website"
git branch -M main
git remote add origin https://github.com/eballante/eballante.github.io.git
git push -u origin main
```

In GitHub, go to:

Settings -> Pages

and set:

- Source: Deploy from a branch
- Branch: main
- Folder: /docs

If the `docs/` folder is not visible yet, run `quarto render` before committing.
