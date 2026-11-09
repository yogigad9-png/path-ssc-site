# PATH SSC — Official Website

Live at: **https://<your-username>.github.io/path-ssc-site/**

Static, mobile-responsive website for the PATH SSC app. Hosted on GitHub Pages.

## Pages
- `index.html` — home / overview
- `privacy-policy.html` — privacy policy (required for Google Play)
- `terms.html` — terms of service
- `data-safety.html` — data safety declaration (mirrors Play Console form)
- `contact.html` — contact + account deletion

## Run locally
```bash
python -m http.server 8080 --directory website
# open http://localhost:8080
```

## Deploy (GitHub Pages)
1. Create a repository, e.g. `path-ssc-site` on GitHub.
2. Push the `website/` contents to the repo (or set the repo root to this folder).
3. Settings → Pages → Source: Deploy from branch → `main` / root → Save.
4. Your site is live at `https://<username>.github.io/path-ssc-site/`.

## Notes
- Update the contact email on all pages if you want a dedicated support address.
- Replace `assets/icon.svg` with the final logo when ready.
