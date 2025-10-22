# 🚀 Quick Start Guide - Alif Online Academy

Get your website live in 5 minutes!

## ✅ What's Included

Your website has:
- ✨ Beautiful single-page design with Islamic aesthetics
- 📱 Fully responsive (mobile, tablet, desktop)
- 🕌 Islamic imagery and calligraphy
- 📖 Authentic Hadith quotes about Quran virtues
- 📚 Three main course sections (Hifz, Tajweed, Tilawa)
- 📧 Contact/enrollment form
- 🎨 Modern animations and transitions
- ⚡ Fast loading and optimized

## 🎯 Files in This Project

```
alifonlineacademy/
├── index.html              ← Main website file (OPEN THIS IN BROWSER)
├── styles.css              ← All styling and design
├── script.js               ← Interactive features
├── README.md               ← Full project documentation
├── DEPLOYMENT.md           ← Detailed deployment guide
├── QUICKSTART.md           ← This file
├── robots.txt              ← SEO configuration
├── sitemap.xml             ← SEO sitemap
├── CNAME.example           ← Custom domain template
└── .gitignore              ← Git configuration
```

## 👀 Preview Locally

**Option 1: Double-click**
- Just double-click `index.html` to open in your browser!

**Option 2: Local Server (Recommended)**
```bash
# If you have Python installed:
python -m http.server 8000

# Then visit: http://localhost:8000
```

## 🌐 Deploy to GitHub Pages (3 Steps)

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Name: `alifonlineacademy`
3. Make it Public
4. Click "Create repository"

### Step 2: Upload Files
**Easy Way (Web Upload):**
1. Click "uploading an existing file" on GitHub
2. Drag these files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
   - `robots.txt`
   - `sitemap.xml`
3. Commit changes

**Terminal Way:**
```bash
cd /home/frappe/alifonlineacademy
git init
git add .
git commit -m "🚀 Launch Alif Online Academy"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/alifonlineacademy.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** (left sidebar)
3. Source: Select `main` branch
4. Click **Save**
5. Wait 2 minutes ⏱️
6. Your site is live! 🎉

**Your URL:** `https://YOUR-USERNAME.github.io/alifonlineacademy/`

## ✏️ Customize Your Website

### 1. Update Contact Info
Open `index.html` and search for:
- `admin@alifonlineacademy.in` → Your current email (update if needed)
- `+91 8078 252 610` → Your current phone number (update if needed)

### 2. Change Colors
Open `styles.css` (lines 7-15) and modify:
```css
--primary-color: #2c5f2d;    ← Main green
--secondary-color: #d4af37;  ← Gold accent
```

### 3. Add Your Social Media
In `index.html`, find the footer section and update social links with your actual URLs.

### 4. Modify Content
Edit any text in `index.html`:
- Course descriptions
- Academy information
- Statistics (students, teachers, etc.)
- Working hours

## 📋 Before Going Live Checklist

- [ ] Update email address and phone number
- [ ] Add your actual social media links
- [ ] Review all course information
- [ ] Test the contact form
- [ ] Check on mobile device
- [ ] Update sitemap.xml with your actual URL
- [ ] Update robots.txt with your actual URL
- [ ] Review and customize welcome message

## 🎨 Design Features

1. **Hero Section**: Eye-catching intro with gradient background
2. **Hadith Quotes**: 4+ authentic hadiths about learning Quran
3. **Courses**: Hifz, Tajweed, Tilawa with detailed info
4. **Gallery**: Islamic calligraphy and imagery
5. **Features**: 6 key benefits of the academy
6. **Contact Form**: Easy enrollment system
7. **Responsive**: Works on all devices

## 🔧 Common Tasks

### Update a Section
1. Open `index.html`
2. Find the section (they're clearly labeled with comments)
3. Edit the text
4. Save and refresh browser

### Change an Image
1. Find the image section in `index.html`
2. Replace the `src="..."` URL with your image URL
3. Save and refresh

### Add Google Analytics
Add this before `</body>` in `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🆘 Need Help?

### Website Not Loading on GitHub Pages?
- Wait 3-5 minutes after first deployment
- Check Settings → Pages is enabled
- Verify files are in root directory

### Form Not Submitting?
- Currently shows alert only (no backend)
- To get real submissions, use:
  - [Formspree](https://formspree.io/) (easiest)
  - [Netlify Forms](https://www.netlify.com/products/forms/)
  - [Google Forms](https://www.google.com/forms/)

### Want Custom Domain?
1. Buy domain from Namecheap, GoDaddy, etc.
2. Rename `CNAME.example` to `CNAME`
3. Put your domain in the CNAME file
4. Update DNS settings to point to GitHub
5. Add custom domain in GitHub Pages settings

## 📚 Additional Resources

- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [HTML Tutorial](https://www.w3schools.com/html/)
- [CSS Tutorial](https://www.w3schools.com/css/)
- [JavaScript Basics](https://www.w3schools.com/js/)

## 🤲 Final Notes

This website is built with care to help spread Quranic knowledge. May Allah accept this effort and make it beneficial for many students.

**"The best among you are those who learn the Quran and teach it."**
*- Prophet Muhammad ﷺ (Sahih Bukhari)*

---

## 🎯 Quick Command Reference

```bash
# Test locally
python -m http.server 8000

# Git commands
git add .
git commit -m "Update message"
git push

# Check status
git status
```

**Need more help?** Check `DEPLOYMENT.md` for detailed instructions!

---

Made with ❤️ for spreading Quranic knowledge






