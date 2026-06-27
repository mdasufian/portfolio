# Abu Sufian — Portfolio

Personal portfolio site for **Abu Sufian**, Senior Software Engineer (10 years in .NET, JavaScript, and cloud).

Built as a single-page static site with plain HTML, CSS, and JavaScript — no build step, no dependencies.

## Live site

Hosted on GitHub Pages: **https://mdasufian.github.io/portfolio/**

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy to GitHub Pages

1. Push to the `main` branch of this repo.
2. In your repo on GitHub: **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Pick branch `main` and folder `/ (root)`. Save.
5. Wait ~1 minute, then visit `https://<your-username>.github.io/portfolio/`.

## Structure

```
.
├── index.html       # markup and content
├── styles.css       # design system + responsive layout
├── script.js        # theme toggle, scroll reveal, smooth scroll
└── CV of Abu Sufian.pdf
```

## Customize

- Content lives in `index.html` (hero, about, experience, skills, projects, contact).
- Colors and theme tokens are CSS variables at the top of `styles.css`.
- Dark mode is the default; click the toggle in the nav to switch.
