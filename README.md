# Thế Giới Sách Tuổi Trẻ

This is a small static website of book summaries. The site is ready to be hosted on GitHub Pages.

What I created for you:
- `README.md` — this file
- `.gitignore` — common ignores
- `.github/workflows/pages.yml` — GitHub Actions workflow to deploy the repo to GitHub Pages on push to `main`

How to publish (quick):
1. Create a new repository on GitHub (via website or `gh repo create`).
2. Add the remote and push:

```powershell
cd "c:\Users\admin\Downloads\New folder (4)"
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

3. Wait for the Actions workflow to finish (Actions → `pages.yml`). Your site will be published under `https://<your-username>.github.io/<repo-name>/` (or the repo root if you use a custom domain).

If you want, I can also try to create the remote repo using `gh` if you have the GitHub CLI and are signed in. Let me know.
