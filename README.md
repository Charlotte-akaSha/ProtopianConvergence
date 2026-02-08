# Protopian Convergence Website

A static website for Protopian Convergence - regenerative gatherings for a thriving civilization.

## Local Development

To run this site locally, simply open `index.html` in your web browser. No server or build process is required.

### Option 1: Direct File Opening
1. Navigate to the project directory
2. Double-click `index.html` or right-click and select "Open with" your preferred browser

### Option 2: Using a Local Server (Recommended)
For better compatibility and to avoid CORS issues, you can use a simple local server:

**Python 3:**
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000 in your browser.

**Node.js (if you have it installed):**
```bash
npx http-server
```

**PHP:**
```bash
php -S localhost:8000
```

## Project Structure

```
.
├── index.html          # Homepage
├── about.html          # About page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── assets/
│   └── images/         # Image assets
└── README.md           # This file
```

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it (e.g., `protopian-convergence-website`)
3. Do NOT initialize with README, .gitignore, or license (we already have these)

### Step 2: Push Your Code
```bash
# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Static website for Protopian Convergence"

# Add your GitHub repository as remote (replace with your repo URL)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**
7. Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Step 4: Custom Domain (Optional)
If you want to use a custom domain:
1. Add a `CNAME` file in the root directory with your domain name
2. Configure DNS settings with your domain provider to point to GitHub Pages
3. See [GitHub Pages documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) for details

## Notes

- **Forms**: The contact form has been replaced with a placeholder. To restore functionality, integrate with a service like Formspree, Netlify Forms, or similar.
- **Dynamic Content**: Any server-side functionality from the original Wix site has been removed and replaced with static content or TODO comments.
- **Images**: All images have been downloaded and stored locally in the `assets/images/` directory.

## Browser Support

This site works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

Copyright © 2024 Protopian Convergence. All rights reserved.
