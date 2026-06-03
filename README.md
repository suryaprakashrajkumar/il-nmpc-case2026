# Paper Webpage

Static academic webpage for:

**A Real-Time Affordable Predictive Trajectory Tracking Controller for Differential Drive Robots via Imitation Learning**

Accepted at IEEE CASE 2026.

Open `index.html` directly in a browser, or serve the folder with any static file server:

```bash
python3 -m http.server 8000
```

The page was generated from `../main_ver6.tex` and uses local previews in `assets/`.

## GitHub Pages Deployment

Use a standalone project repository so the existing portfolio repository remains unchanged.

Recommended repository name:

```text
il-nmpc-case2026
```

After creating the empty repository on GitHub:

```bash
git remote add origin git@github.com:suryaprakashrajkumar/il-nmpc-case2026.git
git push -u origin main
```

Then enable Pages in the new repository only:

- Settings -> Pages
- Source: Deploy from a branch
- Branch: `main`
- Folder: `/root`

The site URL will be:

```text
https://suryaprakashrajkumar.github.io/il-nmpc-case2026/
```
