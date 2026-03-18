# Coming Soon

A personal "coming soon" landing page for an upcoming project.

## Preview

Open `index.html` in a browser, or visit the live site once deployed.

## Deploy to GitHub Pages

1. Create a **new repo** on your **personal** GitHub (not company org):
   - Go to https://github.com/new
   - Name it something like `coming-soon` or `<your-username>.github.io` (for root domain)
   - Set to **Public**

2. Push this code:
   ```bash
   git remote add origin https://github.com/<your-username>/coming-soon.git
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Repo → Settings → Pages
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
   - Save

4. Your site will be live at:
   `https://<your-username>.github.io/coming-soon/`

## Custom Domain (Optional)

If you own a domain, add a `CNAME` file with your domain name and configure DNS:
- Add an A record pointing to GitHub Pages IPs
- Or a CNAME record pointing to `<your-username>.github.io`

## Email Collection

Currently emails are stored in `localStorage` (client-side demo). For production:
- **Free**: [Formspree](https://formspree.io) — swap the form action
- **Free**: [EmailJS](https://www.emailjs.com) — send emails from JS
- **Self-hosted**: Add a small backend (Cloudflare Worker, Vercel Function, etc.)
