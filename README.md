# Elena Walsh website migration

This is the first page of a clean, static replacement for the Squarespace site. It uses only HTML and CSS and can be hosted directly with GitHub Pages.

## What is included

- `publications/index.html` — the rebuilt Publications page
- `assets/css/styles.css` — the shared site styling
- `assets/documents/` — four PDFs moved off Squarespace
- `index.html` — temporary redirect to the Publications page
- `.nojekyll` — tells GitHub Pages to serve the files as written

The navigation links for pages not yet migrated still point to the live Squarespace site. Replace those links with local paths as each page is rebuilt.

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `elena-walsh-website`.
2. Upload all files and folders from this project, preserving the folder structure.
3. Open the repository's **Settings**.
4. Select **Pages** under **Code and automation**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder, then save.
7. GitHub will provide the public Pages address after deployment.

## Preview locally

From the project folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000/publications/`.

## Before cancelling Squarespace

Rebuild the remaining pages, download every image and document still hosted by Squarespace, test all links, and only then update the domain records or cancel the Squarespace plan.
