# Sai Krishna — Embedded Systems Portfolio

A responsive static portfolio website built with HTML, CSS and JavaScript. It is ready to publish using GitHub Pages.

## Files
- `index.html` — portfolio content and page structure
- `style.css` — responsive dark technical theme
- `script.js` — mobile navigation and current year
- `assets/Sai-Krishna-Resume.pdf` — resume download
- `assets/profile-photo.jpg` — profile image used in the hero section
- `assets/profile-formal.jpg` — optional alternate portrait
- `assets/project-*.jpg` — AI-generated project illustrations
- `assets/hero-tech.jpg` — technology banner image
- `assets/portfolio-design-reference.png` — original visual design reference (if included)

## Publish with GitHub Pages
1. Sign in to GitHub and create a **new public repository**. A convenient name is `embedded-portfolio`.
2. Extract this ZIP file on your computer.
3. Open the new repository and choose **Add file → Upload files**.
4. Upload the *contents* of the `embedded-portfolio` folder (not the enclosing folder): `index.html`, `style.css`, `script.js`, `README.md`, and the `assets` folder.
5. Commit the files to the `main` branch.
6. Open **Settings → Pages** in the repository.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch **main** and folder **/(root)**, then click **Save**.
9. Wait a minute or two and refresh the Pages settings. GitHub will show the published website URL.

For a repository named `embedded-portfolio`, the URL is normally:
`https://YOUR-GITHUB-USERNAME.github.io/embedded-portfolio/`

If you instead name the repository `YOUR-GITHUB-USERNAME.github.io`, the site is published at:
`https://YOUR-GITHUB-USERNAME.github.io/`

## Update the portfolio
Edit `index.html` for text and project details, `style.css` for appearance, and `script.js` for interactions. Upload the updated files to the same repository and commit; GitHub Pages republishes automatically.

## Before publishing
Check the phone number, email, LinkedIn URL and resume PDF. Replace any detail that has changed. The content is based on the supplied resume.


## Latest visual update
The hero technology banner now uses `background-size: contain` and a matching aspect ratio so the full STM32/nRF/ESP32 chip artwork remains visible. Platform badges for NVIDIA Jetson, Raspberry Pi and Linux are included in the banner.


## Version 4 updates
- Responsive layout recalibrated for wide desktop, laptop, tablet and mobile widths.
- The hero artwork now keeps a stable aspect ratio and scales consistently rather than leaving oversized blank bands.
- Added dedicated project illustrations for Raspberry Pi 5 OverlayFS file protection and STM32 GPS auto-healing.
- The two new project images are stored locally in `assets/`, so GitHub Pages does not need external image hosting.

When updating an existing repository, replace `index.html`, `style.css`, and upload the complete updated `assets/` folder.
