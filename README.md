# NXE — Final Static Website (No Xcuse)
This is the updated, ready-to-deploy static website template for your esports team **NXE (No Xcuse)**.
Files included:
- `index.html` — main page (updated roster)
- `style.css` — styling (dark esports theme)
- `README.md` — deploy instructions

## Quick deploy to GitHub Pages
1. Create a GitHub account (if you don't have): https://github.com
2. Create a new repository named **username.github.io** (replace `username` with your GitHub username).
3. Upload `index.html` and `style.css` to the repository (root folder).
4. Go to **Settings > Pages** and enable Pages from `main` branch. Your site will be live at `https://username.github.io`

## Connect a custom domain (Freenom example)
1. Register a free domain at https://www.freenom.com (e.g. `nxe.tk`).
2. In your GitHub repo `Settings > Pages` set the custom domain to `yourdomain.tk`.
3. In Freenom DNS settings, add these records:
   - A @ → 185.199.108.153
   - A @ → 185.199.109.153
   - A @ → 185.199.110.153
   - A @ → 185.199.111.153
   - CNAME www → username.github.io
4. Wait DNS propagation (few minutes to hours), then enable **Enforce HTTPS** on GitHub Pages.

## Customize
- Edit roster names & roles in `index.html`.
- Replace avatars with images (put them in repo and update `<div class="avatar">` to `<img src="...">`)
- Change colors in `style.css` to match your brand.
