# Atelier

Single-page site for private arrangements. By referral only.

## Contents

- `index.html` — Full site (hero, philosophy, inquiry form) with smooth section scrolling.
- `DEPLOY.md` — How to deploy to a free host (Netlify, Surge, Vercel, GitHub Pages).

## Publish to a new private Git repository

The repo is already initialized with an initial commit. To publish to GitHub:

1. **Create the private repo on GitHub**
   - Go to [github.com/new](https://github.com/new).
   - Repository name: `atelier` (or any name).
   - Set visibility to **Private**.
   - Do **not** add a README, .gitignore, or license (this folder already has them).
   - Click **Create repository**.

2. **Add the remote and push** (run in PowerShell from this folder):

```powershell
cd C:\Users\email\atelier-deploy
git remote add origin https://github.com/YOUR_USERNAME/atelier.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username. If GitHub prompts for credentials, use a [Personal Access Token](https://github.com/settings/tokens) instead of your password.
