# Deploy Atelier to a free domain

Your site is in the `atelier-deploy` folder. Use **one** of these options to get a free URL.

---

## Option 1: Netlify Drop (no account needed for first deploy)

1. Open **https://app.netlify.com/drop**
2. Drag the **atelier-deploy** folder onto the page.
3. Netlify will give you a URL like `random-name-123.netlify.app`.
4. To keep the same URL and manage updates, create a free Netlify account when prompted.

**Free subdomain:** `something.netlify.app`

---

## Option 2: Surge (from terminal)

1. Open PowerShell or Command Prompt.
2. Run:
   ```bash
   cd C:\Users\email\atelier-deploy
   npx surge .
   ```
3. First time: enter email and set a password when asked.
4. It will show a URL like `something.surge.sh`. You can type a custom name when it asks for a domain (e.g. `atelier.surge.sh` if it’s free).

**Free subdomain:** `your-choice.surge.sh`

---

## Option 3: Vercel (from terminal)

1. Open PowerShell or Command Prompt.
2. Run:
   ```bash
   cd C:\Users\email\atelier-deploy
   npx vercel
   ```
3. Log in when the browser opens (GitHub, GitLab, or email).
4. Accept the defaults (press Enter). You’ll get a URL like `atelier-deploy-xxx.vercel.app`.

**Free subdomain:** `your-project.vercel.app`

---

## Option 4: GitHub Pages

1. Create a new repo on GitHub (e.g. `atelier`).
2. Push the contents of `atelier-deploy` (only `index.html`) to the repo.
3. In the repo: **Settings → Pages** → Source: **Deploy from a branch** → branch: **main** → folder: **/ (root)** → Save.
4. After a minute, the site is at `https://yourusername.github.io/atelier/`.

**Free subdomain:** `yourusername.github.io/repo-name`

---

After deploying, open the URL you get to view your Atelier site. To update the site, change files in `atelier-deploy` and deploy again the same way.
