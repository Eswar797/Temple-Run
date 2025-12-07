# GitHub Setup Instructions

## After creating a repository on GitHub, run these commands:

Replace `YOUR_USERNAME` and `REPO_NAME` with your actual GitHub username and repository name.

```bash
cd "C:\Users\Eswar Narayana\Desktop\supermario"

# Add the remote repository (replace with your actual GitHub URL)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Rename branch to main (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

## Alternative: If you prefer SSH

```bash
git remote add origin git@github.com:YOUR_USERNAME/REPO_NAME.git
git branch -M main
git push -u origin main
```

## Quick Setup (if you have GitHub CLI installed)

```bash
gh repo create temple-run-web --public --source=. --remote=origin --push
```

