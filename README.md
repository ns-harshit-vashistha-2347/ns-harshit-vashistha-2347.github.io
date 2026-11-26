# Harshit Vashistha — Portfolio

A single-page static site: plain HTML, CSS and a little JavaScript. There's no build step and nothing to install.

## Files

- `index.html` is the whole site.
- `resume.pdf` is the file the "Download resume" button links to. Replace it whenever you update your resume, and keep the same name.
- `.nojekyll` tells GitHub Pages to serve the files as they are.

## Deploy free on GitHub Pages (about 5 minutes)

1. Create a new **public** repository on GitHub named **`<your-username>.github.io`**. Your site will then live at `https://<your-username>.github.io`.
2. Upload `index.html`, `resume.pdf` and `.nojekyll` to the repo: click **Add file → Upload files**, drag them in, then **Commit**.
3. Open **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, **Branch: `main` / `(root)`**, then **Save**.
4. Wait 1–2 minutes and open `https://<your-username>.github.io`.

If you prefer the command line:

```bash
git init
git add .
git commit -m "Portfolio site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

## Other free hosts

- **Netlify Drop:** go to https://app.netlify.com/drop and drag this folder onto the page. The site is live right away.
- **Vercel / Cloudflare Pages:** import the GitHub repo; no build command and output directory `/`.

## What to edit

Search `index.html` for `EDIT:` comments:

- **GitHub button:** add your GitHub URL in the Contact section and uncomment it.
- **AI-102 credential:** paste your Microsoft Learn share link and uncomment it.
- **Lumen:** add a demo or GitHub link and real numbers (for example retrieval recall or answer accuracy) once you have them.

The accent colour is `--accent` at the top of the `<style>` block.
