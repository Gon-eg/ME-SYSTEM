# Bath Research & Analytics System

A health indicator tracking console for facility-level monthly reporting.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g., `bath-research`)
2. Upload these files to the repo:
   - `index.html` (the main app)
   - `README.md` (this file)
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**
7. Wait 1-2 minutes, then visit:
   ```
   https://YOUR_USERNAME.github.io/bath-research/
   ```

## Important Notes

- The file **must** be named `index.html` — GitHub Pages looks for this filename by default
- If you name it anything else (e.g., `ME_project.html`), you'd need to visit:
  ```
  https://YOUR_USERNAME.github.io/bath-research/ME_project.html
  ```
- A blank page usually means the filename is wrong or Pages isn't enabled yet

## Alternative: Deploy via Command Line

```bash
# Create repo and push
git init
git add index.html README.md
git commit -m "Initial deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/bath-research.git
git push -u origin main
```

Then enable Pages in Settings as described above.

## Features

- Upload facility reports (.xlsx / .docx) → indicators auto-fill
- Manual entry for indicators without file sources
- Save/load monthly data (stored in browser localStorage)
- Export to CSV, Excel (.xlsx), and Word (.doc)
- Progress tracking with cumulative totals

## Author

James Gon
