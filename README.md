# Tippy Thai House – demo website

A one-page demo website for Tippy Thai House, Colchester. It's plain HTML, so it runs on GitHub Pages as-is.

**This is a mockup.** Orders, checkout and stamp-card sign-ups are not real.

## Put it online with GitHub Pages
1. Create a new public repository on GitHub (e.g. `tippy-thai-demo`).
2. Click **Add file → Upload files**, drag in `index.html`, `README.md` and `.nojekyll`, then **Commit changes**.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and **Save**.
4. After a minute or two it's live at `https://<your-username>.github.io/tippy-thai-demo/`.

## Editing the menu
The whole menu is in the `const M=[...]` list near the bottom of `index.html`. Each dish has a name (`n`),
description (`d`), price (`p`) and `from: true` if the price is a "from" price.
