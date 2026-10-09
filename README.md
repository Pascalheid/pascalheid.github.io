# Pascal Heid — academic website

Prepared for https://pascalheid.github.io/.

## Publish on GitHub Pages

1. Create a public repository in the Pascalheid account named `pascalheid.github.io` and initialize it with a README.
2. Upload this folder's contents to the repository root. Keep `index.html`, `images/`, and `documents/` beside one another; do not upload their parent folder or the ZIP.
3. Open Settings → Pages. Select Deploy from a branch, choose `main` and `/ (root)`, then Save.
4. Visit https://pascalheid.github.io/ once deployment completes.

This uses the address already printed in the CV. No purchased domain or DNS configuration is needed.

## PDFs

- CV: `documents/CV_Pascal_Heid.pdf`
- Job market paper: `documents/JMP_Pascal_Heid.pdf`
- Electric vehicle paper: `documents/ev_paper_hrr_29052026.pdf`

The PDFs are hosted alongside the HTML. Their links are direct file links, suitable for sharing and opening without JavaScript. To update a paper or the CV, replace the PDF at the same path and commit the change; no HTML change is required. The PDF contents are unchanged from the supplied files.

All text and styling are in `index.html`. The portrait is in `images/pascal-heid.jpg`. There is no build step.

Official guide: https://docs.github.com/en/pages/quickstart
