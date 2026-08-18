# Your Name — Biotech Research Portfolio

A responsive, single-page scientific/biotech portfolio designed for GitHub Pages.

## Folder structure

```text
your-website/
├── index.html
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── main.js
│   ├── images/
│   │   └── README.txt
│   └── cv.pdf
└── README.md
```

## Before publishing

Search the files for these placeholders and replace them:

- `Your Name`
- `YN`
- `your.email@example.com`
- `https://www.linkedin.com/`
- `https://scholar.google.com/`

Also replace the sample publication entries and timeline information with your final details.

## Adding your CV

Put your PDF in:

`assets/cv.pdf`

The CV button already points to that filename.

If your file has another name, update the link in `index.html`.

## Adding images

Place photographs, research figures, or other images in:

`assets/images/`

Example:

```html
<img src="assets/images/research-platform.jpg" alt="Description of research platform">
```

## Test locally

The site is static, so you can open `index.html` directly in a browser.

For a closer GitHub Pages-like environment, you can also use VS Code with the Live Server extension.

## Publish with GitHub Pages

1. Create a GitHub repository named:

   `YOURUSERNAME.github.io`

2. Upload the contents of this folder to the repository's main branch.

3. On GitHub, open:

   `Settings → Pages`

4. Under "Build and deployment", choose:

   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`

5. Save.

6. After GitHub finishes building the site, visit:

   `https://YOURUSERNAME.github.io`

## Custom domain

After the basic site works, you can connect a custom domain through:

`Settings → Pages → Custom domain`

Do not attempt this until the GitHub Pages version is working.
