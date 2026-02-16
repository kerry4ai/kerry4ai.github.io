# Kerui Du - Academic Website

Professional academic website for Kerui Du (杜珂锐), Associate Professor at China Institute for Studies in Energy Policy, School of Management, Xiamen University.

## 🌟 Features

- **Professional academic design** - Clean, elegant layout suitable for faculty profiles
- **Responsive** - Works on all devices (desktop, tablet, mobile)
- **Modern UI** - Smooth animations, hover effects, and interactive elements
- **Google Scholar integration** - Direct links to publications
- **SEO optimized** - Proper meta tags and semantic HTML

## 📊 Academic Highlights

- **Total Citations**: 8,407
- **h-index**: 37
- **i10-index**: 51

## 🔬 Research Interests

- Applied Econometrics
- Energy Economics
- Environmental Economics
- Industrial Economics

## 📁 File Structure

```
kerui-du-academic/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## 🚀 Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Create a new repository named: `yourusername.github.io` (replace with your GitHub username)
   - OR create any repository name, then enable GitHub Pages in settings

### Step 2: Upload Files

**Option A: Using Git Command Line**

```bash
# Initialize git repository
cd kerui-du-academic
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Academic website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Desktop**

1. Download GitHub Desktop: https://desktop.github.com/
2. Open the `kerui-du-academic` folder
3. Create repository and publish to GitHub

**Option C: Upload via Web Interface**

1. Go to your repository on GitHub
2. Click "Add file" > "Upload files"
3. Drag and drop `index.html`, `style.css`, and `script.js`
4. Commit changes

### Step 3: Enable GitHub Pages

1. Go to repository **Settings** → **Pages**
2. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click **Save**
4. Wait 1-2 minutes for deployment
5. Your site will be live at: `https://YOUR_USERNAME.github.io/`

## ✏️ Customization

### Update Personal Information

Edit `index.html`:

1. **Email**: Find `keruidu@xmu.edu.cn` and replace with your email
2. **Profile Photo**: Replace the placeholder with your photo:
   ```html
   <div class="profile-placeholder">
       <i class="fas fa-user"></i>
   </div>
   ```
   Change to:
   ```html
   <img src="your-photo.jpg" alt="Kerui Du" class="profile-photo">
   ```

3. **Publications**: Add more papers in the publications section
4. **Courses**: Update teaching section with your courses

### Color Scheme

Edit `style.css` to change colors:

```css
:root {
    --primary-color: #2c3e50;      /* Dark blue */
    --secondary-color: #3498db;    /* Blue */
    --accent-color: #27ae60;       /* Green */
}
```

## 📝 Adding Publications

To add a new publication, copy this template in `index.html`:

```html
<article class="publication-item">
    <div class="pub-citation">
        <span class="citation-count">XXX</span>
        <span class="citation-label">citations</span>
    </div>
    <div class="pub-content">
        <h3>Your Paper Title</h3>
        <p class="pub-authors"><strong>Du, K.</strong>, Co-author, A.</p>
        <p class="pub-journal"><em>Journal Name</em>, Volume, Pages (Year)</p>
    </div>
</article>
```

## 🔗 Useful Links

- **Google Scholar**: https://scholar.google.com/citations?user=hHQkDmUAAAAJ
- **Institution**: https://cicep.xmu.edu.cn/info/1033/1515.htm
- **Xiamen University**: https://www.xmu.edu.cn/

## 📄 License

This website template is free to use for academic purposes.

## 👤 Author

**Kerui Du**
- Associate Professor
- China Institute for Studies in Energy Policy
- School of Management, Xiamen University
- Email: keruidu@xmu.edu.cn

---

Created with ❤️ for academic professionals
