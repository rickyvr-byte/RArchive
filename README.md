RArchive
=========

Quick instructions to publish this project to GitHub Pages or use as a webapp.

Steps to push to GitHub:

```bash
# from inside the repository folder
git init
git add .
git commit -m "Initial commit: RArchive website"
git remote add origin https://github.com/<your-username>/RArchive.git
git branch -M main
git push -u origin main
```

To test locally:

```bash
# from this folder
python -m http.server 8000
# open http://localhost:8000/index.html
```

Notes
- `index.html` (lowercase) is the site entry point.
- `ProjectsDisplay.json` contains project metadata (images, titles, `url`).
- If you deploy via Google Apps Script webapp, copy the needed files there or use GitHub as source.

If you want, I can create the GitHub repository and push the files for you (you will need to provide an access token).
