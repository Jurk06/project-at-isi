# Deploying to GitHub Pages

## Quick Start

Your Jekyll website is now ready to deploy! Follow these steps:

### Step 1: Update Repository Configuration

Edit `_config.yml` and update:
- Replace `your-email@example.com` with your actual email
- The `url` should point to your GitHub Pages URL: `https://YOUR-USERNAME.github.io`
- The `baseurl` stays as `/project-at-isi` (your repo name)

```yaml
url: https://your-github-username.github.io
baseurl: /project-at-isi
```

### Step 2: Push to GitHub

If not already done, initialize git and push to your GitHub repository:

```bash
# From the project-at-isi directory
git add .
git commit -m "Initial Jekyll site setup"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings**
3. Scroll to **Pages** section
4. Under "Build and deployment":
   - Source: Select **GitHub Actions**
   - This will automatically use the Jekyll workflow

### Step 4: Verify Deployment

1. GitHub will automatically build and deploy your site
2. Check the **Actions** tab to see the build progress
3. Once complete, your site will be available at:
   ```
   https://YOUR-USERNAME.github.io/project-at-isi/
   ```

## Local Testing (Optional)

To test the site locally before pushing:

### Prerequisites
- Ruby 3.1+ installed
- Bundler installed

### Commands

```bash
# From project-at-isi directory

# Install dependencies
bundle install

# Build and serve locally
bundle exec jekyll serve

# Visit http://localhost:4000/project-at-isi/ in your browser
```

## Site Structure

```
project-at-isi/
├── _config.yml              # Jekyll configuration
├── Gemfile                  # Ruby dependencies
├── index.md                 # Homepage
├── docs/
│   ├── anova.md            # ANOVA Analysis page
│   ├── visualization.md    # Geographic visualization
│   ├── imputation.md       # Missing data imputation
│   ├── trends.md           # Trend analysis
│   ├── clustering.md       # Clustering analysis
│   └── about.md            # About page
├── .github/workflows/
│   └── jekyll-deploy.yml   # Auto-deploy workflow
├── assets/
│   └── css/                # Custom stylesheets (optional)
├── _layouts/               # Custom layouts (optional)
└── _includes/              # Custom includes (optional)
```

## Customization

### Change Theme
Edit `_config.yml`:
```yaml
# Current theme
remote_theme: pages-themes/cayman@v0.2.0

# Available themes:
# - pages-themes/cayman@v0.2.0
# - pages-themes/minimal@v0.2.0
# - pages-themes/slate@v0.2.0
# - pages-themes/architect@v0.2.0
# - pages-themes/tactile@v0.2.0
# - pages-themes/merlot@v0.2.0
# - pages-themes/time-machine@v0.2.0
```

### Add Navigation Menu
Create `_includes/navigation.html` (optional) or update `_layouts/default.html`

### Add Custom CSS
Create files in `assets/css/` and reference in layouts

## Troubleshooting

### Site not showing?
- Ensure `GitHub Actions` is enabled in repository settings
- Check the Actions tab for build errors
- Verify `baseurl` matches your repository name

### Incorrect links?
- Check `_config.yml` baseurl and url settings
- Use `{{site.baseurl}}` prefix for all internal links

### Need to hide data files?
Update `.gitignore` if you don't want to commit CSV/XLSX files

## Further Resources

- [Jekyll Official Documentation](https://jekyllrb.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Pages + Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)

---

**Questions?** Check the repository issues or refer to the project README.md
