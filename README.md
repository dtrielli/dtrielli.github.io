# Daniel Trielli — personal website

A small static website for https://dtrielli.github.io/. Plain HTML and embedded CSS; no JavaScript, frameworks, analytics, or build process. Lato loads from Google Fonts with Arial/system fallbacks. Maryland red (#e21833), a white background, and thin red rules follow the supplied C+J slides.

## Publish on GitHub Pages

1. Unzip this package and copy the **contents** of `dtrielli-website/` into the root of your `dtrielli.github.io` repository. Replace its existing `index.html`. Include `favicon.svg`, `.nojekyll`, and the `assets/` folder.
2. Commit and push the files.
3. In the repository, open **Settings → Pages**. If Pages already deploys from the repository root, keep that configuration. Otherwise choose **Deploy from a branch**, select your default branch, and choose **/ (root)**. Save.
4. Open https://dtrielli.github.io/ after deployment finishes.

Keep unrelated repository files. No custom domain file is included. If your repository has a `CNAME` file for a custom domain, retain or remove it according to where you want the website published.

## Edit

Edit the text and links directly in `index.html`. Replace `assets/daniel-trielli-cv.docx` when updating your CV, keeping the same filename. Update the footer date when updating content.

The page works when opened directly from disk. For a local preview you can also run `python3 -m http.server 8000` from this folder and open http://localhost:8000.

## Content sources

- Current CV supplied by Daniel, retrieved September 22, 2026 version; included unchanged as a Word download.
- https://merrill.umd.edu/directory/daniel-trielli
- https://danieltrielli.com/about-me/
- https://scholar.google.com/citations?user=UQG_ypEAAAAJ
- https://brand.umd.edu/colors
- AI News Game C+J 2026 slides supplied by Daniel (visual reference and game link).
- Publication DOI links and Nieman Lab article linked directly in the page.

The site presents selected publications, rather than claiming to be a complete publication list. Planned teaching is labeled as planned. Citation metrics and unpublished paper details are omitted to avoid rapidly outdated information.
