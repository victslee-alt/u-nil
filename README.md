# Portfolio Deployment Guide

This project is a static site. You can deploy it as-is on GitHub Pages, Vercel, or Netlify.

## Files

- `index.html`
- `validation.html`
- `styles.css`
- `script.js`
- `assets/`

## Recommended: GitHub Pages

1. Create a GitHub repository.
2. Push this folder to the repository root.
3. In GitHub, open `Settings > Pages`.
4. Set `Build and deployment` to `Deploy from a branch`.
5. Select the default branch and `/ (root)`.
6. Save and wait for the public URL to be issued.

## Alternative: Vercel

1. Import the GitHub repository into Vercel.
2. Keep framework preset as `Other`.
3. Leave build command empty.
4. Leave output directory empty.
5. Deploy.

## Alternative: Netlify

1. Import the GitHub repository into Netlify.
2. Leave build command empty.
3. Set publish directory to `.`
4. Deploy.

## Notes

- All image paths now use relative paths under `assets/`, so they are deploy-safe.
- The HTML files are UTF-8 and should render Korean correctly in browsers.
