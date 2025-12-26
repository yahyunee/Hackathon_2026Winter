# 🚀 Quick Deployment Guide

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. **Repository name:** `Hackathon_2026Winter`
3. **Description:** "2026 Neuro-AI Grand Hackathon - Official Website"
4. **Visibility:** Public (required for GitHub Pages)
5. **DO NOT** initialize with README, .gitignore, or license
6. Click **Create repository**

## Step 2: Push Your Code

Copy and paste these commands in your terminal (you're already in the right directory):

```bash
# Add GitHub as remote
git remote add origin https://github.com/yahyunee/Hackathon_2026Winter.git

# Push to GitHub
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under "Build and deployment":
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `(root)`
   - Click **Save**

## Step 4: Wait & View

- Wait 2-3 minutes for GitHub Pages to build your site
- Your website will be live at:

  **https://yahyunee.github.io/Hackathon_2026Winter/**

- You can check build status in: Settings → Pages → GitHub Pages section

## 🎉 Done!

Your hackathon website is now live!

### Making Updates

Whenever you want to update the website:

```bash
# Make your changes to the files
# Then:
git add .
git commit -m "Update: describe your changes"
git push
```

GitHub Pages will automatically rebuild and deploy within 1-2 minutes.

---

## 🛠️ Local Development (Optional)

To preview changes before pushing:

```bash
# Install dependencies (first time only)
bundle install

# Run local server
bundle exec jekyll serve

# View at: http://localhost:4000/Hackathon_2026Winter/
```

---

## 📋 Quick File Reference

- **Homepage:** `en/index.md` or `kr/index.md`
- **Overview:** `en/overview.md` or `kr/overview.md`
- **Projects:** `en/projects.md` or `kr/projects.md`
- **Tutorials:** `en/tutorials.md` or `kr/tutorials.md`
- **Styling:** `assets/css/style.css`
- **Layout:** `_layouts/default.html`
- **Configuration:** `_config.yml`

---

## ❓ Troubleshooting

### Site not showing up?
- Check Settings → Pages to see build status
- Make sure repository is **Public**
- Verify the branch is set to `main` / `(root)`

### Images or links broken?
- All links should use `{{ '/path/to/file' | relative_url }}`
- Check `_config.yml` has correct `baseurl: "/Hackathon_2026Winter"`

### Need help?
- GitHub Pages docs: https://docs.github.com/en/pages
- Jekyll docs: https://jekyllrb.com/docs/

---

**Good luck with your hackathon! 🧠✨**
