# Git Setup and Push Instructions

## Your repository has been initialized and committed locally!

### Option 1: Push to a New GitHub Repository

1. **Create a new repository on GitHub:**
   - Go to https://github.com/new
   - Name it "Diplomat" or your preferred name
   - Don't initialize with README (we already have files)
   - Click "Create repository"

2. **Connect and push to GitHub:**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

### Option 2: Push to an Existing Repository

If you already have a repository:
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

### Check Current Status

```bash
# View commit history
git log --oneline

# Check repository status
git status

# View remote repositories
git remote -v
```

### Future Updates

After making changes:
```bash
# Stage all changes
git add .

# Commit with a message
git commit -m "Your commit message here"

# Push to GitHub
git push
```

### Common Git Commands

```bash
# Create a new branch
git checkout -b feature-name

# Switch branches
git checkout main

# Pull latest changes
git pull origin main

# View differences
git diff
```

## Current Commit

✅ Initial commit completed with:
- index.html (main website)
- styles.css (custom styles)
- assets/images/ (logo and images)
- README.md (project documentation)
- PROJECT_STRUCTURE.md (file structure guide)
- .gitignore (ignore unnecessary files)

## Next Steps

1. Create a GitHub repository
2. Copy the remote URL
3. Run the commands above with your repository URL
4. Your website will be pushed to GitHub!

## Deploy to GitHub Pages (Optional)

After pushing to GitHub:
1. Go to repository Settings
2. Navigate to Pages section
3. Select "main" branch as source
4. Your site will be live at: https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
