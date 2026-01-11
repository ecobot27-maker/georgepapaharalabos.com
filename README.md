# Portfolio website — Dr. George Papaharalabos

This is a clean, professional, single-page portfolio website with chapters from 2011 onward.
It is intentionally designed so you can **add your own project images later**.

## Add images later (easy)
- Put your images in `/assets`
- Replace any `<img src="assets/placeholder.jpg">` references in `index.html` with your image filenames
- Or overwrite `assets/placeholder.jpg` with your preferred default placeholder (updates everywhere)

## Publish with your name as the URL (georgepapaharalabos.com)
### GitHub Pages + Custom Domain (typical)
1. Create a GitHub repo named `georgepapaharalabos.com` (or any name).
2. Upload these files to the repo root.
3. GitHub repo Settings → Pages → set Source to the `main` branch.
4. Connect your custom domain in Pages settings.
5. Add DNS records at your domain registrar.

A `CNAME` file is included and currently set to `georgepapaharalabos.com`.

### Netlify / Vercel
Upload this folder (Netlify drag-and-drop) or import the repo (Vercel), then connect the custom domain.

## Files
- `index.html` — content
- `styles.css` — styling
- `script.js` — minimal JS (mobile nav, footer year)
- `/assets` — images (placeholders + your own later)
