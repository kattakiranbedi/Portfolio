# Katta Kiran Bedi — Portfolio

Personal portfolio website for Katta Kiran Bedi, Software Engineer & Frontend Developer based in Hyderabad, India.

## Live Site

Once deployed, your portfolio will be at:
`https://<your-github-username>.github.io/<repository-name>/`

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript
- Google Fonts (Inter + Poppins)
- No build tools or frameworks required

## How to Deploy on GitHub Pages

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in.
2. Click **New repository**.
3. Name it `portfolio` (or anything you like).
4. Set visibility to **Public**.
5. Click **Create repository**.

### Step 2 — Upload Files

**Option A — Upload via GitHub web UI (easiest):**
1. Open your new repository.
2. Click **Add file → Upload files**.
3. Drag and drop both `index.html` and `style.css`.
4. Click **Commit changes**.

**Option B — Using Git CLI:**
```bash
cd f:/portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click **Settings** → **Pages** (left sidebar).
3. Under **Source**, select **Deploy from a branch**.
4. Choose branch: `main`, folder: `/ (root)`.
5. Click **Save**.
6. Wait ~1–2 minutes, then visit the URL shown.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Full portfolio — all sections and JavaScript |
| `style.css` | All styling, responsive design, animations |
| `README.md` | This deployment guide |

## Sections

- **Hero** — Name, title, and quick intro
- **About** — Professional summary and key stats
- **Skills** — Technical skills by category
- **Projects** — 3 case studies (E-Learning, BET, Vastraloop)
- **Experience** — WEXL AI work history
- **Education** — MCA & Bachelor's degree
- **Contact** — Email, phone, GitHub, location
