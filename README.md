## TTTrading KH App Privacy Page

This repository contains the static Privacy Policy page for the TTTrading KH
internal POS and inventory application.

- **Live page:**  
  `https://ichamrong.github.io/tttradingkh-app-privacy/`

Use this URL as the **Privacy Policy URL** in:

- App Store Connect (iOS)
- Google Play Console (Android)

---

### Project structure

- `index.html` – The Privacy Policy page shown on GitHub Pages.

You can open and edit `index.html` directly to update the policy text, last
updated date, or styling.

---

### How GitHub Pages is configured

This repo is published using **GitHub Pages**:

1. Go to **Settings → Pages** in this repository.
2. **Source** is set to:  
   - `Deploy from a branch`  
   - Branch: `main`  
   - Folder: `/ (root)`
3. GitHub builds and serves the site at:  
   `https://ichamrong.github.io/tttradingkh-app-privacy/`

If you ever fork or rename the repository, GitHub Pages will change the URL to
match the new owner or repo name.

---

### Updating the Privacy Policy

1. Edit `index.html` (for example, to change:
   - Company/app name
   - Contact email (`info@tttradingkh.com`)
   - Text in any section of the policy
2. Commit the changes:

   ```bash
   git add index.html
   git commit -m "Update privacy policy text"
   git push
   ```

3. Wait a minute for GitHub Pages to redeploy, then refresh  
   `https://ichamrong.github.io/tttradingkh-app-privacy/`.
