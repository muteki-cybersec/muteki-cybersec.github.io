# Muteki

Personal landing page and contact card. OSINT · GEOINT · System Administration · Network Engineering.

Live: https://muteki-cybersec.github.io/

## License and artwork terms

This repository is split into two parts with different terms. Full text: [LICENSE](LICENSE).

| Part | Files | Terms |
|------|-------|-------|
| Source code | `index.html` (HTML, CSS) | [MIT License](LICENSE) |
| Muteki Artwork | `logo.png`, `project.png`, and copies, vector representations or redrawings of the composition | **All Rights Reserved** |

### Muteki Artwork

The hexagonal node composition, the arrangement of the elements around it and its visual styling are original work by Muteki, copyright (c) 2026.

You may not copy, re-host, redistribute, trace or redraw this composition, or use it (or a recreation of it) as your own logo, avatar or branding, without written permission. Redrawing it from scratch with a different tool does not change this.

Forking this repository on GitHub is allowed only as far as the GitHub Terms of Service provide. It does not give you any right to use the artwork elsewhere.

### Third-party marks

The artwork shows the names or logos of SimpleX Chat, Monero, Mullvad VPN, Tor Browser, Bitwarden and Tails. These belong to their respective owners. No rights in them are claimed here, and their presence does not imply affiliation or endorsement.

### Permission requests and reports

Contact details are on the [website](https://muteki-cybersec.github.io/).
Unauthorized use may be reported to the hosting platform under the DMCA and pursued under applicable law.

## Deploy to GitHub Pages

Upload `index.html`, `logo.png`, `project.png`, `.nojekyll`, `README.md` and `LICENSE` to the root of the `main` branch in the `muteki-cybersec.github.io` repository. Keep the filenames unchanged.

In the repository, open **Settings → Pages**, select **Deploy from a branch**, then **main** and **/ (root)**, and save. No build or package installation is required.

`logo.png` is the image displayed on the page; `project.png` is used for the favicon and link previews.

## Local preview

With Python 3 installed, run this command from the project directory:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765/ in your browser. Press Ctrl+C in the terminal to stop the server. This serves the HTML and its images together, including in browsers that cannot access adjacent files when an HTML file is opened through the desktop file portal.
