# 📦 Architecture Design Website - Complete Package

## 🎉 Package Contents

This package contains everything you need to deploy your architecture design website to GitHub Pages.

### 📁 Files Included:

1. **index.html** - Main website (English, USD pricing)
2. **admin.html** - Admin dashboard for management
3. **README.md** - Complete documentation (English)
4. **DEPLOYMENT_GUIDE_VI.md** - Detailed deployment guide (Vietnamese)
5. **QUICK_START.md** - Quick 5-minute deployment guide
6. **deploy.sh** - Automated deployment script
7. **.gitignore** - Git ignore configuration
8. **LICENSE** - MIT License

---

## 🚀 Quick Deploy (3 Steps)

### Step 1: Create GitHub Repository
1. Go to: https://github.com/new
2. Repository name: `architecture-design-website`
3. Select **Public**
4. Click **Create repository**

### Step 2: Upload Files
Choose ONE method:

**Method A - Using Deploy Script (Easiest):**
```bash
cd architecture-design-website
./deploy.sh
```

**Method B - Manual Git Commands:**
```bash
cd architecture-design-website
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR-USERNAME/architecture-design-website.git
git branch -M main
git push -u origin main
```

**Method C - GitHub Web Upload:**
1. Open your repository on GitHub
2. Click "uploading an existing file"
3. Drag and drop all files
4. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Click **Pages** in left sidebar
3. Under **Source**, select `main` branch
4. Click **Save**
5. Wait 2 minutes

**Your website will be live at:**
`https://YOUR-USERNAME.github.io/architecture-design-website/`

---

## 📖 Documentation Guide

### For Beginners:
1. Start with: **QUICK_START.md** (5-minute guide)
2. If issues: **DEPLOYMENT_GUIDE_VI.md** (detailed Vietnamese guide)

### For Experienced Users:
1. Run `./deploy.sh` script
2. Or use manual Git commands
3. Check **README.md** for customization

---

## 🎨 Website Features

### Main Website (index.html)
- 6 Product Categories
- Featured Products Section
- Responsive Design
- Contact Information
- Modern UI/UX

### Admin Dashboard (admin.html)
- Dashboard with Statistics
- Product Management (Add/Edit/Delete)
- Category Management
- Order Tracking
- Settings Configuration

---

## 🔧 Customization

### Change Products:
Edit product cards in `index.html`:
```html
<div class="product-price">$99</div>
<h3 class="product-title">Your Product Name</h3>
```

### Change Contact Info:
Update in both files:
```html
<span>📞 Hotline: +1 (555) 123-4567</span>
<span>📧 Email: info@archdesignplans.com</span>
```

### Change Colors:
Modify CSS gradient in `<style>` section:
```css
background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
```

---

## 📊 GitHub Pages URLs

After deployment, your site will be accessible at:

- **Main Website**: `https://USERNAME.github.io/REPO-NAME/`
- **Admin Panel**: `https://USERNAME.github.io/REPO-NAME/admin.html`

Example:
- `https://johndoe.github.io/architecture-design-website/`
- `https://johndoe.github.io/architecture-design-website/admin.html`

---

## 💡 Pro Tips

✅ **Use short repository names** - They become part of your URL
✅ **Repository must be Public** - For free GitHub Pages
✅ **Clear browser cache** - If changes don't show
✅ **Wait 1-2 minutes** - After each update
✅ **Use Incognito mode** - To test without cache

---

## 🆘 Common Issues & Solutions

### Issue: "git: command not found"
**Solution:** Install Git from https://git-scm.com/downloads

### Issue: "Permission denied" on deploy.sh
**Solution:** Run `chmod +x deploy.sh`

### Issue: Website shows 404
**Solution:** 
- Check file is named `index.html` (lowercase)
- Wait 5 minutes after enabling GitHub Pages
- Clear browser cache

### Issue: Changes not visible
**Solution:**
- Clear cache (Ctrl + Shift + Delete)
- Try incognito mode
- Wait 2-5 minutes for GitHub to rebuild

### Issue: "Repository not found"
**Solution:** Create repository on GitHub first: https://github.com/new

---

## 📞 Support & Resources

- **GitHub Pages Docs**: https://pages.github.com/
- **Git Documentation**: https://git-scm.com/doc
- **GitHub Community**: https://github.community/

---

## 📝 Update Checklist

When updating your website:

- [ ] Edit HTML files (index.html, admin.html)
- [ ] Test locally (open in browser)
- [ ] Commit changes: `git commit -am "Update message"`
- [ ] Push to GitHub: `git push origin main`
- [ ] Wait 1-2 minutes
- [ ] Clear browser cache
- [ ] Check live site

---

## 🎯 Next Steps

After deployment:

1. ✅ Test all pages and links
2. ✅ Add real product images
3. ✅ Update contact information
4. ✅ Connect custom domain (optional)
5. ✅ Add Google Analytics (optional)
6. ✅ Set up payment gateway (future)
7. ✅ Add backend API (future)

---

## 📄 File Structure

```
architecture-design-website/
├── index.html                  # Main website
├── admin.html                  # Admin dashboard
├── README.md                   # Main documentation
├── DEPLOYMENT_GUIDE_VI.md      # Vietnamese deploy guide
├── QUICK_START.md             # Quick start guide
├── deploy.sh                   # Deployment script
├── .gitignore                  # Git ignore file
└── LICENSE                     # MIT License
```

---

## 🌟 Features at a Glance

| Feature | Main Site | Admin Panel |
|---------|-----------|-------------|
| Product Catalog | ✅ | ✅ |
| Categories | ✅ | ✅ |
| Pricing (USD) | ✅ | ✅ |
| Shopping Cart | ✅ | - |
| Product Management | - | ✅ |
| Order Tracking | - | ✅ |
| Settings | - | ✅ |
| Responsive Design | ✅ | ✅ |

---

## 🎨 Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Hosting**: GitHub Pages (Free)
- **Version Control**: Git
- **No Dependencies**: Pure vanilla code

---

## 📈 Future Enhancements

Suggested improvements:

- [ ] Backend API integration
- [ ] User authentication
- [ ] Payment gateway (Stripe/PayPal)
- [ ] Database connection
- [ ] Email notifications
- [ ] Search functionality
- [ ] Image upload feature
- [ ] Multi-language support
- [ ] SEO optimization
- [ ] Analytics dashboard

---

## 🙏 Thank You

Thank you for using this template! If you find it helpful:

- ⭐ Star the repository
- 🐛 Report issues
- 💡 Suggest improvements
- 🤝 Contribute via pull requests

---

## 📜 License

This project is licensed under the MIT License - see LICENSE file for details.

---

**Made with ❤️ in Vietnam**

🌐 **Deploy now and get your website online in 5 minutes!**

---

*For detailed instructions, please refer to the documentation files included in this package.*
