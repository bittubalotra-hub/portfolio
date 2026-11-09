# Bitu Kumar — Aerospace Portfolio Website

A static, responsive portfolio site ready for GitHub Pages. The main image has been replaced with the supplied new portrait.

## Project contents

```text
Bitu_Kumar_GitHub_Portfolio/
├── index.html                  # Website page
├── styles.css                  # All layout and responsive styles
├── assets/
│   ├── bitu-kumar-portrait.jpg # Optimized cropped display photo
│   ├── bitu-kumar-original.jpg # Full user-supplied photo
│   └── favicon.svg             # Browser tab icon
├── .nojekyll                   # GitHub Pages compatibility
└── README.md                   # This file
```

## Local preview

Double-click `index.html` to preview in a browser, or run a simple static server:

```bash
python -m http.server 8000
```

Then browse to `http://localhost:8000`.

## Deploy using GitHub Pages (no build required)

1. Sign in to GitHub and create a **new public repository**, e.g. `bitu-kumar-portfolio`.
2. Upload the **contents** of this folder to the repository root. `index.html` must be in the root, not in a nested subfolder.
3. Commit changes to the `main` branch.
4. Go to the repo's **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**. Select branch `main` and folder `/ (root)`; click **Save**.
6. When Pages finishes publishing, open `https://YOUR-USERNAME.github.io/bitu-kumar-portfolio/`.

For a repo named `YOUR-USERNAME.github.io`, the URL will be `https://YOUR-USERNAME.github.io/` instead.

## Updating the photo

Replace `assets/bitu-kumar-portrait.jpg` with a new image using the **same filename**, and commit the change. For a different crop, edit the portrait image or `.portrait-outline img` CSS rule in `styles.css`.

## Before public publishing

- Review the contact email and telephone number. Publishing this site makes them visible on the internet.
- This draft retains a small note that the personal career and academic claims came from a supplied profile and should be independently verified before being represented as factual.
- This is a self-contained site with **no external libraries, APIs, or build tools required**.
