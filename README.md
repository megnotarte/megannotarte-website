# megannotarte-website

Personal website hosted on GitHub Pages. No build step — plain HTML/CSS/JS in a single file.

**Live site:** https://megnotarte.github.io/megannotarte-website/

---

## Making edits

All content lives in `index.html`. Open it in any text editor and make your changes.

## Deploying changes

Every push to `main` automatically updates the live site (usually within 1–2 minutes).

```bash
# After editing index.html:
git add index.html
git commit -m "Update site content"
git push
```

Then visit the live URL above to confirm the update.

## Previewing locally

Open `index.html` directly in your browser — no server needed:

```bash
open index.html   # macOS
# or just double-click the file in Finder
```

## GitHub Pages setup (already done)

Pages is enabled under **Settings → Pages → Source: Deploy from branch → main / (root)**.
No CI, no build process — GitHub serves `index.html` directly.
