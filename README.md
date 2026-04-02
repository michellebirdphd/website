# Simple GitHub Pages Website

This project is a lightweight static website designed to deploy cleanly to
GitHub Pages through GitHub Actions.

## Structure

- `index.html` is the landing page.
- `blog/` contains the blog index and individual post pages.
- `projects/` contains the projects index and individual project pages.
- `styles.css` contains the shared site styling.
- `scripts/site.js` contains the small shared JavaScript used by the pages.
- `.github/workflows/deploy-pages.yml` publishes the site to GitHub Pages when
  changes are pushed to `main`.

## Editing content

To add a new blog post:

1. Create a new HTML file in `blog/`.
2. Copy the structure from an existing post like `blog/starting-small.html`.
3. Add a new card linking to it in `blog/index.html`.

To add a new project page:

1. Create a new HTML file in `projects/`.
2. Copy the structure from an existing project like `projects/north-window.html`.
3. Add a new card linking to it in `projects/index.html`.

## GitHub Pages setup

After pushing this repository to GitHub:

1. Open the repository on GitHub.
2. Go to `Settings` > `Pages`.
3. Under `Build and deployment`, set `Source` to `GitHub Actions`.
4. Push to `main` or run the workflow manually from the `Actions` tab.

GitHub Actions will publish the repository contents as a static site.
