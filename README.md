# Tech Orbit Media — Website

Three pages, plain HTML/CSS/JS, no build step required:

- `index.html` — Home (services, tech accessories, recent work, contact)
- `about.html` — About
- `work.html` — Our Work (portfolio)

All images are embedded directly in each file (no separate image folder needed), so the whole site is just these self-contained HTML files.

## How to launch it

Any static hosting works. A few easy options:

**Netlify (easiest)**
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag this whole `tech-orbit-media` folder onto the page
3. You get a live URL immediately — you can add a custom domain afterwards in Site settings

**GitHub Pages**
1. Create a new GitHub repo and upload these 3 files (plus this README)
2. In the repo's Settings → Pages, set the source to the `main` branch, root folder
3. Your site will be live at `https://<username>.github.io/<repo-name>/`

**Your own hosting / cPanel**
Upload the 3 HTML files to your `public_html` (or equivalent) folder via FTP or the file manager. That's it — no server-side code, no dependencies.

## Before you launch

- Double check the WhatsApp number, email and social links in the footer/contact section are still correct
- If you add more pages later, keep the same folder (don't rename `index.html`, `about.html` or `work.html` without updating the links in each file's navigation menu)
