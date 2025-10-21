# GitHub Pages Deployment Guide

Quick guide to deploy Alif Online Academy website to GitHub Pages.

## Prerequisites

- A GitHub account
- Git installed on your computer (optional, can use GitHub web interface)

## Step-by-Step Deployment

### Option 1: Using GitHub Web Interface (Easiest)

1. **Create a New Repository**
   - Go to [GitHub](https://github.com)
   - Click the "+" icon in the top right
   - Select "New repository"
   - Name it: `alifonlineacademy` (or any name you prefer)
   - Make it Public
   - Don't initialize with README (we already have one)
   - Click "Create repository"

2. **Upload Files**
   - On the repository page, click "uploading an existing file"
   - Drag and drop all files from the `alifonlineacademy` folder:
     - `index.html`
     - `styles.css`
     - `script.js`
     - `README.md`
   - Click "Commit changes"

3. **Enable GitHub Pages**
   - Go to your repository's Settings
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select branch: `main` (or `master`)
   - Leave folder as `/ (root)`
   - Click "Save"

4. **Access Your Website**
   - Wait 2-3 minutes for deployment
   - Your site will be live at: `https://[your-username].github.io/alifonlineacademy/`
   - GitHub will show the URL in the Pages settings

### Option 2: Using Git Command Line

1. **Initialize and Push to GitHub**

```bash
# Navigate to the project folder
cd /home/frappe/alifonlineacademy

# Initialize git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial commit: Alif Online Academy website"

# Create main branch (if needed)
git branch -M main

# Add your GitHub repository as remote
# Replace YOUR-USERNAME with your GitHub username
git remote add origin https://github.com/YOUR-USERNAME/alifonlineacademy.git

# Push to GitHub
git push -u origin main
```

2. **Enable GitHub Pages**
   - Follow steps 3-4 from Option 1 above

## Custom Domain (Optional)

If you have a custom domain:

1. Create a file named `CNAME` (no extension) in your repository
2. Add your domain name in it (e.g., `www.alifonlineacademy.com`)
3. Configure your domain's DNS settings:
   - Add CNAME record pointing to: `[your-username].github.io`
4. In GitHub Pages settings, add your custom domain

## Updating Your Website

### Via GitHub Web Interface:
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon to edit
4. Make changes and commit

### Via Git Command Line:
```bash
# Make your changes to the files
# Then:
git add .
git commit -m "Description of your changes"
git push
```

Changes will appear on your live site within 1-2 minutes.

## Troubleshooting

### Site Not Loading
- Wait 3-5 minutes after first deployment
- Check that GitHub Pages is enabled in settings
- Verify branch name is correct (main or master)

### Images Not Showing
- Check image URLs in HTML
- Ensure paths are correct (relative paths work best)
- Clear browser cache

### CSS Not Applied
- Check that `styles.css` is in the same folder as `index.html`
- Clear browser cache
- Check for typos in the `<link>` tag

### Form Not Working
- The form currently shows an alert
- For actual form submission, you'll need to:
  - Use a form service like Formspree, Netlify Forms, or Google Forms
  - Set up a backend server
  - Or integrate with an email service

## Making the Site Your Own

### Update Contact Information
Edit `index.html` and change:
- Email address (line ~333)
- Phone/WhatsApp number (line ~340)
- Social media links (line ~415)

### Change Academy Name/Logo
Edit `index.html`:
- Update `<title>` tag (line 6)
- Change logo text (lines 18-19)
- Update all references to "Alif Online Academy"

### Modify Colors
Edit `styles.css` variables (lines 7-15):
```css
--primary-color: #2c5f2d;    /* Change to your color */
--secondary-color: #d4af37;  /* Change to your color */
```

## Performance Tips

1. **Images**: Consider hosting images locally for faster loading
2. **Compression**: Minify CSS and JS for production
3. **Caching**: GitHub Pages handles this automatically
4. **Analytics**: Add Google Analytics code before `</body>` tag if needed

## Security & Privacy

- Don't commit sensitive information (API keys, passwords)
- Use environment variables for sensitive data
- For production, consider using a contact form service instead of showing email directly

## Need Help?

- GitHub Pages Documentation: https://docs.github.com/en/pages
- Git Tutorial: https://git-scm.com/docs/gittutorial
- GitHub Support: https://support.github.com

---

**May your website be a source of knowledge and guidance for many! 🤲**






