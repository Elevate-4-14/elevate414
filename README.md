# Elevate 4:14 website

A plain HTML/CSS site with no build step. Open `index.html` in a browser to preview it.

## Files
- `index.html` (Home), `about.html`, `services.html`, `resources.html`: one file per page. The header and footer are repeated in each, so update all four if you change the menu.
- `styles.css` – styles; brand colors are at the top under `:root`
- `assets/` – logo (color + white), favicon

## Before launch: fill these in (search for "TODO")
- Optional: team headshots (put them in `assets/team/` and swap the initials)

## Deploy to GitHub Pages
1. Create a GitHub repo and push these files to the `main` branch.
2. In the repo, open Settings → Pages. Set Source to "Deploy from a branch", then pick `main` and `/ (root)`.
3. Custom domain: enter the domain under Settings → Pages → Custom domain. This creates a `CNAME` file.
4. At the domain registrar, add DNS records:
   - `A` records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` for `www` → `<your-github-username>.github.io`
5. After DNS propagates, check "Enforce HTTPS".
