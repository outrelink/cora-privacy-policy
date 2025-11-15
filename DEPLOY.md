# Quick Deploy Guide

## Option 1: GitHub Web Interface (Easiest)

1. Go to https://github.com/new
2. Repository name: `cora-privacy-policy`
3. Make it **Public**
4. Check "Add a README file"
5. Click "Create repository"

6. Click "uploading an existing file"
7. Drag and drop `privacy-policy.html`
8. Click "Commit changes"

9. Go to Settings → Pages
10. Source: "Deploy from a branch"
11. Branch: "main", Folder: "/ (root)"
12. Click "Save"

13. Wait 1-2 minutes, then visit:
    `https://YOUR-USERNAME.github.io/cora-privacy-policy/privacy-policy.html`

## Option 2: Using Git Commands

```bash
# Create repository on GitHub first, then:
cd /Users/zahra/cora-privacy-policy
git remote add origin https://github.com/YOUR-USERNAME/cora-privacy-policy.git
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository Settings → Pages.

## Option 3: Netlify Drop (No Account Needed!)

1. Go to https://app.netlify.com/drop
2. Drag the entire `cora-privacy-policy` folder
3. Get instant URL like: `https://random-name-123.netlify.app/privacy-policy.html`
4. Done! No account needed.

