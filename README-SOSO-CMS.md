# SOSO CMS upgrade

This version of SOSO uses GitHub Pages + Jekyll + Pages CMS.

## Why this is easier
Once installed, you can add a place from a form instead of editing HTML:
1. Go to https://app.pagescms.org
2. Sign in with GitHub.
3. Install/authorize the Pages CMS GitHub App for `sosocolorado/sososite`.
4. Open the repository.
5. Choose **Places & Adventures**.
6. Click **New**.
7. Fill in the form, upload a photo, and save.
8. GitHub Pages rebuilds the public site automatically.

## Upload these files
Replace your existing `index.html`, then add:
- `_config.yml`
- `.pages.yml`
- `style.css`
- `_layouts/place.html`
- the entire `_places/` folder
- `images/` folder (can be empty)

GitHub Pages should keep using:
- branch: `main`
- folder: `/ (root)`

## Note
The configured `baseurl` is `/sososite`. If you rename the repository later, update `_config.yml`.
