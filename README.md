# GAON LAB — First public website

A no-build, no-paid-server personal experiment archive. `index.html` is the home page. `projects/moon-jar/index.html` contains the real interactive WebGL experiment. `notes/moon-jar-research.html` is the provenance-based research notebook.

## Preview locally

1. Unzip the download.
2. Double-click `index.html` (open in Chrome). The moon jar also runs as a local HTML page.
3. Follow "EXPLORE PROJECT" to play with the 3D object. From the project footer, choose "← GAON LAB" to return.

## Publish free on GitHub Pages

1. Sign into https://github.com and find your GitHub **username** (not your display name).
2. New repository → repository name must be exactly `USERNAME.github.io`, substituting your username. Set visibility to **Public**.
3. From the new repo choose **Add file → Upload files**, then drag the *contents of the unzipped folder* onto GitHub (not the .zip itself and not the parent folder).
4. Verify files at repo root include `index.html`, `.nojekyll`, `assets/`, `projects/`, and `notes/`. To ensure hidden `.nojekyll` gets uploaded, if necessary create it separately; not strictly required for this vanilla HTML version.
5. Commit the changes. In repository **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, then Save.
6. After publishing, visit `https://USERNAME.github.io/`.

Notes: Publication can take a few minutes. The repository is **public**. Don't upload secrets, addresses, private photos, credentials, CVs with contact info, or API keys.

## Add another project

1. Create `projects/new-project/index.html` (your new working demo).
2. Edit the home page `index.html` and add a new linked project card.
3. Upload changes to the same repository and commit; GitHub Pages updates the live website automatically.

## Custom domain later (optional)

No domain purchase or server payment required. The free `.github.io` domain works. You can purchase a domain later and configure it in GitHub Pages settings.

## Content integrity

- The 3D jar is **not** a scan or reconstruction of any museum artifact; it is an original experimental shape.
- Museum facts come from eMuseum / National Museum of Korea, the British Museum and Christie's, linked on the research page.
- The original moon jar screenshot is an internal screenshot of the prototype, not a museum image.
- The site uses an externally loaded Google Fonts stylesheet, but functionality doesn't depend on it.
