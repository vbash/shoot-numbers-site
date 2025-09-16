# GitHub Pages Setup Instructions

Follow these steps to enable your documentation site:

## 1. Push to GitHub

First, commit and push all files to your GitHub repository:

```bash
git add .
git commit -m "Add GitHub Pages documentation site with privacy policy"
git push origin main
```

## 2. Enable GitHub Pages

1. Go to your GitHub repository
2. Click on **Settings** tab
3. Scroll down to **Pages** section (in left sidebar)
4. Under **Source**:
   - Select "Deploy from a branch"
   - Branch: **main** (or **master** if that's your default)
   - Folder: **/docs**
   - Click **Save**

## 3. Your Site URLs

After a few minutes, your site will be available at:

- **Main site**: `https://vbash.github.io/Shoot-Numbers/`
- **Privacy Policy**: `https://vbash.github.io/Shoot-Numbers/privacy-policy/`

## 4. Update Configuration

Edit `docs/_config.yml` and update:
- Replace `vbash` with your GitHub username
- Replace `Shoot-Numbers` with your actual repository name
- Update the email address in the privacy policy

## 5. Use Privacy Policy URL

Copy the privacy policy URL and use it in:
- App Store Connect (Privacy Policy URL field)
- Your app's settings or about section

## 6. Custom Domain (Optional)

If you have a custom domain:
1. Add a `CNAME` file in the `/docs` folder with your domain
2. Configure your domain's DNS to point to GitHub Pages
3. Update the URLs in your App Store Connect

## Troubleshooting

- **Site not loading**: Wait 5-10 minutes after enabling Pages
- **404 errors**: Check that branch and folder settings are correct
- **Build failures**: Check the Actions tab for error details

## Next Steps for App Store

1. Wait for your site to be live (test the privacy policy URL)
2. Copy the privacy policy URL: `https://vbash.github.io/Shoot-Numbers/privacy-policy/`
3. Use this URL in App Store Connect when submitting your app
