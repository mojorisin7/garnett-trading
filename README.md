# Garnett Trading - Coming Soon Page

A simple, responsive static HTML coming soon page for Garnett Trading.

## Setup for GitHub Pages

1. Push this repository to GitHub
2. Go to your repository settings on GitHub
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose the `main` (or `master`) branch and `/ (root)` folder
6. Click "Save"
7. Your site will be available at `https://[your-username].github.io/garnett-trading/`

## Custom Domain Setup (Future)

When you're ready to use a custom domain:

1. Add a `CNAME` file in the root directory with your domain name (e.g., `www.yourdomain.com`)
2. Configure your DNS settings with your domain provider:
   - Add a CNAME record pointing to `[your-username].github.io`
3. Update the GitHub Pages settings to use your custom domain

## Files

- `index.html` - Main page with embedded CSS (no external dependencies)
- `.gitignore` - Git ignore file for macOS/editor files
- `README.md` - This file

## Customization

To customize the page:
- Edit `index.html` directly
- Update the background image URL in the `.hero` CSS class
- Modify contact information, social media links, and text content
- Adjust colors and styling in the `<style>` section

