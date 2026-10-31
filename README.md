# Wallpaper site

Marketing website for a custom printed wallpaper design and installation service. It is a single static file (`index.html`) with no build step.

## Edit before launch

Open `index.html` and change the `CONFIG` block at the top of the `<script>`: brand name, city, phone number (`phoneDigits` is country code + number, digits only), and email. Material prices are in `MATERIALS` just below it.

## Deploy

- **GitHub Pages:** Settings → Pages → Deploy from branch `main`, folder `/ (root)`.
- **Vercel:** vercel.com/new → Import this repo → Deploy (no settings needed).
- **Netlify:** app.netlify.com → Add new site → Import from GitHub → this repo.
