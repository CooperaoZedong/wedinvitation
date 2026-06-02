# Wedding Invitation — GitHub Pages deployment

This folder is ready for GitHub Pages.

## Files

- `index.html` — the invitation page. GitHub Pages needs the main entry file to be named `index.html`.
- `.nojekyll` — disables Jekyll processing so the file is served as plain static HTML.

## Quick deployment

1. Create a new GitHub repository, for example `wedding-invitation`.
2. Upload `index.html` and `.nojekyll` to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** main
   - **Folder:** / (root)
5. Save and wait for the Pages deployment to finish.
6. Open the published URL:
   `https://<your-github-username>.github.io/<repository-name>/`

## Notes

- The page is static HTML/CSS/JS, so no server is required.
- The invitation uses external Google Fonts and React/Babel CDN scripts, so guests need internet access when opening it.
- GitHub Pages is public by default. Do not include private addresses, phone numbers, hidden guest lists, or anything you do not want publicly accessible.
