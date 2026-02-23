[README.md](https://github.com/user-attachments/files/25497669/README.md)
# LMS Slider (GitHub Pages quick start)

## Deploy on GitHub Pages
1) Create a **public** repo (e.g., `lms-slider`).
2) Upload both files: `slider.html` and `README.md` (this readme).
3) Go to **Settings → Pages**:
   - **Build and deployment**: *Deploy from a branch*
   - **Branch**: `main` and **/ (root)**
4) Wait ~1–2 minutes. The Pages URL will be:
   `https://<your-username>.github.io/lms-slider/slider.html`
5) Use that URL in your Docebo iFrame widget (height ~380–420px).

## Common 404 causes
- Wrong URL path: it must end with `/slider.html` (case-sensitive).
- Pages not enabled or deploying from the wrong branch/folder.
- Private repo (must be public for GitHub Pages unless you use Actions for private).
- First build still running or failed (check **Actions** → `pages-build-deployment`).

## Customize
- In `slider.html` adjust `--height`, `--accent`, `AUTOPLAY_MS`, and replace images/links.
