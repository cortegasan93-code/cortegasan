# Carlos Ortega Sánchez — personal site

This folder is ready to publish on GitHub Pages.

## Structure

- `index.html` → page structure
- `styles.css` → design and layout
- `script.js` → language switching, dynamic content and scrolling rails
- `images/` → portrait and book photo
- `cv/` → English CV file
- `favicon.svg` → site icon

## Publish on GitHub Pages

1. Create a public GitHub repository named `YOURUSERNAME.github.io`.
2. Upload all files in this folder to the repository root.
3. In GitHub: **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`.
6. Save and wait a minute. Your site will appear at `https://YOURUSERNAME.github.io`.

## Manual editing

- Update texts in `script.js` inside:
  - `translations`
  - `academiaItems`
  - `analysisItems`
  - `talksItems`
  - `programsItems`
- Replace photos by keeping the same filenames in `images/`.
- Replace the CV file in `cv/`.
- To add a publication or feature, copy one object in the relevant array and edit the values.
