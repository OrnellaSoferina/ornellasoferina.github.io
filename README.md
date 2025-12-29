# ornellasoferina.github.io
# Ornella Soferina — Author Website

This repository hosts a static author website for the *My Unfolding with El Shaddai* devotional journal series.

## Edit book links, text, and images

### Update text
Open any of the HTML files (e.g., `index.html`, `books.html`, `about.html`) and edit the placeholder text inside the sections.

### Update Amazon links
Search for the placeholder text:
```
[Amazon book link]
```
Replace it with your Amazon product URL in each file where it appears.

### Update cover images
All pages reference a placeholder file name:
```
assets/cover-volume2.png
```
Replace it with your real cover image file name if desired, or keep the same name and swap in your actual file.

## Add your cover images into `/assets/`
1. Export your book covers as PNG files.
2. Name them to match the filenames used in the HTML (e.g., `cover-volume2.png`).
3. Copy them into the `assets/` folder.
4. If you change filenames, update the `<img src="...">` references in the HTML files.

## Publish on GitHub Pages (step-by-step)
1. Push this repository to GitHub if it is not already there.
2. In your GitHub repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Select the **Branch** as `main` (or `master`) and the **/ (root)** folder.
5. Click **Save**.
6. Wait a minute for the site to deploy.
7. Your site will be available at:
   - `https://ornellasoferina.github.io/`

## File overview
- `index.html` — Home page
- `books.html` — Books page
- `about.html` — About the Author page
- `free-gift.html` — Email signup / lead magnet page
- `contact.html` — Contact page
- `assets/style.css` — Shared site styles
- `assets/` — Place your cover images here
