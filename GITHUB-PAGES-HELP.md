# GitHub Pages Setup - Visual Guide

## Step-by-Step Screenshots Guide

### 1. Repository Settings
```
GitHub Repository → Settings Tab (top right) → Pages (left sidebar)
```

### 2. Pages Configuration
```
Source: Deploy from a branch
Branch: main (or master)
Folder: / (root)
[Save Button]
```

### 3. Success Message
```
✅ Your site is published at https://yourusername.github.io/repository-name
```

## Troubleshooting Checklist

### ✅ Repository Requirements:
- [ ] Repository is PUBLIC (not private)
- [ ] You are the repository OWNER
- [ ] Files are uploaded to main/master branch
- [ ] Main file is named "index.html" (lowercase)

### ✅ File Structure Should Look Like:
```
your-repository/
├── index.html
├── styles.css
├── script.js
├── pic.jpg.jpg
└── README.md (optional)
```

### ✅ Common Error Messages:

**"404 - File not found"**
- Check file names (case sensitive)
- Ensure index.html is in root folder
- Wait 5-10 minutes for propagation

**"Page build failed"**
- Check Actions tab for error details
- Usually means invalid HTML/CSS syntax
- Try deploying to Netlify as backup

**"Settings tab not visible"**
- You don't own the repository
- Repository might be private
- Need admin access

## Alternative Hosting Options

### Netlify (Recommended for beginners):
1. Go to netlify.com
2. Drag portfolio folder
3. Get instant URL

### Vercel:
1. Go to vercel.com
2. Connect GitHub
3. Auto-deploy

### GitHub Codespaces (if you have access):
1. Create codespace
2. Use built-in port forwarding
3. Share preview URL

## Quick Test URLs

After deployment, test these URLs:
- https://yourusername.github.io/repository-name/
- https://yourusername.github.io/repository-name/index.html

## Support Contact

If still stuck:
1. Check GitHub Status: status.github.com
2. GitHub Community: github.community
3. Try Netlify as backup option

## Success Indicators

✅ Green checkmark in Pages settings
✅ "Your site is published at..." message
✅ URL loads your portfolio
✅ All images and styles work
✅ Mobile responsive design works

## Next Steps After Success

1. Test portfolio on mobile
2. Share URL on LinkedIn
3. Add URL to resume
4. Update social media profiles
5. Apply to jobs with portfolio link

Good luck! 🚀
