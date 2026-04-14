# Simple GitHub Pages Website

This is a basic static website (HTML + CSS + a tiny JS file).

## Files you will edit most

- `index.html` → homepage content
- `blog/index.html` → blog list page
- `projects/index.html` → projects list page
- `styles.css` → all shared design styles

## Quick edit workflow (beginner-friendly)

1. Open the repo in your editor.
2. Change text in an `.html` file.
3. Change colors/fonts/spacing in `styles.css`.
4. Save.
5. Preview locally:

```bash
python3 -m http.server 8000
```

Then open: `http://localhost:8000`

## Publish to GitHub Pages

1. Commit your changes.
2. Push to `main` on GitHub.
3. Wait for the GitHub Actions Pages workflow to finish.
4. Open your live site URL.

## Current site structure

- Home: overview + featured blog/paper
- Blog: article index + individual post pages
- Projects: project index + individual project pages
