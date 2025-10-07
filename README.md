# CodeNook · AI Website Consultancy (GitHub Pages)

A single‑page static site with a contact form that posts to **Formspree** (no backend needed).

## Quick start

1. **Create a Formspree form** at https://formspree.io/ and copy your **Form ID** (looks like `abcdwxyz`).
2. Open `index.html` and replace:
   ```js
   const FORMSPREE_ID = "YOUR_FORM_ID";
   ```
   with your ID.
3. Commit & push this folder to a GitHub repo.
4. In the repo: **Settings → Pages → Deploy from branch → `main` / root**.
5. Wait 1–2 minutes. Your site will be live at `https://<username>.github.io/<repo>/`.

## Customizing

- **Logo:** Replace `assets/logo.png` with your own (same filename).
- **Colors/Fonts:** The page uses Tailwind via CDN. Adjust classes right in `index.html`.
- **Analytics:** You can drop any analytics script into `<head>`.
- **Alt contact methods:** If you prefer EmailJS or Netlify Forms, swap the form section accordingly.


## Notes
- Form has a hidden honeypot field to mitigate spam.
- All assets are static and GitHub Pages‑friendly.
