# Amber Nest – Performance Tracker

Static website (no build step, no server). Files: `index.html`, `style.css`, `app.js`, `data.js`.

## Put it live on GitHub Pages
1. Create a new GitHub repository (e.g. `amber-nest`) and upload these 4 files + README to the root.
2. Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. After ~1 minute the site is live at `https://<your-username>.github.io/amber-nest/`.
(Netlify / Vercel / Cloudflare Pages also work: just drag the folder in.)

## How data is stored
* Everything you add is saved in the browser's localStorage on the device you use. `data.js` only holds your original Excel data and is used the first time the site opens.
* Use **⬇ Backup** regularly (downloads a .json) and **⬆ Restore** to load it on another phone/laptop. **CSV** exports everything for Excel.
* Clearing browser data erases the saved entries, so keep backups.
* Revenue is always counted in the month of guest check-out.
