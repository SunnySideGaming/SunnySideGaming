# Guide site template (GitHub Pages)

## Publish
1. Create a new GitHub repo (e.g. `ygg-guide`) and upload all these files to the root.
2. Repo **Settings > Pages > Build and deployment**: Source = "Deploy from a branch", Branch = `main`, folder = `/ (root)`.
3. Your site goes live at `https://YOURNAME.github.io/ygg-guide/` in a minute or two.

## Edit
- Search for `YOUR GUIDE NAME`, `[brackets]` and `YYYY-MM-DD` and replace them.
- Colors and fonts: top of `style.css` (`:root` variables).
- New page: copy `leveling.html`, rename it, then add a link to the `<nav>` in every page.
