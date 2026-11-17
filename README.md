# Data with Mehreen

Practical data science, one small project at a time.
Live site: https://mehreengillani.github.io/data-with-mehreen

## Go live (one-time setup)

1. Install Quarto: https://quarto.org/docs/get-started/
2. Preview locally from this folder:
   ```bash
   quarto preview
   ```
3. Create an **empty** repo on GitHub named `data-with-mehreen` (no README).
4. Push and publish:
   ```bash
   git init
   git add .
   git commit -m "Launch Data with Mehreen"
   git branch -M main
   git remote add origin https://github.com/mehreengillani/data-with-mehreen.git
   git push -u origin main
   quarto publish gh-pages
   ```
5. In about a minute, the site is live at the URL above.

## Weekly workflow

1. Copy a folder in `posts/` and rename it, e.g. `posts/netflix-eda/`
2. Write `index.qmd` (set `date`, `categories`, `description`)
3. `quarto preview` to check it
4. Commit, push, then run `quarto publish gh-pages`

## To do
- [ ] Add `profile.jpg` to this folder and uncomment the `image:` line in `about.qmd`
- [ ] Remove `draft: true` from the BreadBasket post when it's ready
