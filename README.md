# Kishore's Notes — Linux GitHub Pages site

This folder is ready to publish as a **Linux-only GitHub Pages download page** for Kishore's Notes 2.0.0.

## Included

- `index.html` — complete responsive landing/download page
- `assets/kishores-notes.png` — application icon
- `downloads/Kishores-Notes-2.0.0-linux-amd64.deb` — recommended Ubuntu/Debian/Mint package
- `downloads/Kishores-Notes-2.0.0-linux-amd64-portable.tar.gz` — portable build
- `downloads/backtest-report.txt` — release backtest report
- `downloads/SHA256SUMS.txt` — checksums
- `.nojekyll` — tells GitHub Pages to serve the site as plain static files

## Publish with GitHub Pages

1. Create a new GitHub repository, for example `kishores-notes-linux`.
2. Upload **all files and folders from this directory to the repository root**.
3. Commit the files to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select `main` and `/ (root)`.
7. Click **Save**.
8. GitHub will show the public Pages address after deployment finishes.

The download buttons in `index.html` use relative links, so they work without editing regardless of the GitHub username or repository name.

## Updating a release

Replace the files in `downloads/`, update the version/file names in `index.html`, regenerate `SHA256SUMS.txt`, commit, and push.

## Architecture

The included release is **Linux amd64 / x86_64 only**.
