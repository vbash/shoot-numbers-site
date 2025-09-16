# Shoot Numbers Documentation Site

This documentation site is built with GitHub Pages and Jekyll.

## Setup Instructions

1. **Enable GitHub Pages**:
   - Go to your repository Settings
   - Scroll to "Pages" section
   - Source: Deploy from a branch
   - Branch: main (or master)
   - Folder: /docs
   - Save

2. **Your site will be available at**:
   `https://[your-username].github.io/[repository-name]/`

3. **Privacy Policy URL**:
   `https://[your-username].github.io/[repository-name]/privacy-policy/`

## Important Notes

- Update the `_config.yml` file with your actual GitHub username and repository name
- Replace `[your-email@example.com]` in the privacy policy with your real contact email
- The site may take a few minutes to build and deploy after pushing to GitHub

## Local Development (Optional)

To test locally before deploying:

```bash
cd docs
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` to preview your site.
