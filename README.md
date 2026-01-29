# Atelier

Single-page site for private arrangements. By referral only.

## Contents

- `index.html` — Full site (hero, philosophy, inquiry form) with smooth section scrolling.
- `DEPLOY.md` — How to deploy to a free host (Netlify, Surge, Vercel, GitHub Pages).

## Publish to a new private Git repository

Run these in a terminal from the `atelier-deploy` folder:

```bash
cd C:\Users\email\atelier-deploy

# Initialize and first commit
git init
git add .
git commit -m "Initial commit: Atelier site"

# Create a new private repo on GitHub and push (requires GitHub CLI)
gh repo create atelier --private --source=. --remote=origin --push
```

If you don't use GitHub CLI, create the repo in the browser first:

1. Go to [github.com/new](https://github.com/new).
2. Name the repo (e.g. `atelier`), set it to **Private**, leave “Add a README” unchecked.
3. Create the repository, then run:

```bash
cd C:\Users\email\atelier-deploy
git remote add origin https://github.com/YOUR_USERNAME/atelier.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.
