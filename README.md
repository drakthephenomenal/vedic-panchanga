# Vedic Panchanga — GitHub Pages Ready

This is a static PWA version of Vedic Panchanga fixed for GitHub Pages deployment.

## What was fixed

1. **Relative paths** — changed `/assets/...` → `./assets/...` and `/icons/...` → `./icons/...`
   so files load correctly from a GitHub Pages subdirectory (`username.github.io/repo-name/`).
2. **Manifest `start_url`** — changed from `/` to `.` so the PWA opens the correct page.
3. **Missing PWA icons** — generated `icon-192.png` and `icon-512.png`.
4. **Added `.nojekyll`** — tells GitHub Pages not to process with Jekyll.

## How to deploy on GitHub Pages

1. Upload all files from this zip to your GitHub repository root.
2. Go to **Settings → Pages** in your GitHub repo.
3. Under **Build and deployment**, select:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or your default branch) → folder `/` (root)
4. Click **Save**.
5. Wait ~1 minute, then visit `https://yourusername.github.io/vedic-panchanga-main/`

## Install as PWA on your phone

- **Android Chrome:** Open the site → tap the menu (⋮) → "Add to Home screen"
- **iOS Safari:** Open the site → tap Share (⬆️) → "Add to Home Screen"
