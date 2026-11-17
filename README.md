# MBANI landing page

This repository hosts the MBANI marketing landing page as a self-contained static site.

## Live site

GitHub Pages publishes the root `index.html` after a push to `main`.

## Local preview

```powershell
python -m http.server 8080 --directory .
```

Then open `http://localhost:8080`.

## Manual Cloudflare deployment

Use [MBANI Cloudflare Deployment Guide.pdf](MBANI%20Cloudflare%20Deployment%20Guide.pdf) for the dashboard steps. The upload package is [mbani-landing-upload.zip](mbani-landing-upload.zip).

## Contents

- `index.html` holds the complete page and its embedded assets.
- `.github/workflows/pages.yml` publishes it to GitHub Pages.
- `MBANI Cloudflare Deployment Guide.pdf` explains how to deploy the same build through Cloudflare Pages.
