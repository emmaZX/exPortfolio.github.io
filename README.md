# Emma Xuan — ePortfolio

A personal portfolio site built for GitHub Pages.

---

## Setup

### 1. Create a GitHub repo
Name it: `YOUR_USERNAME.github.io`  
(Example: `emmaxuan.github.io`)

### 2. Upload these files
Put all files from this folder into the root of that repo. Keep the folder structure:
```
/
├── index.html
├── about.html
├── projects.html
├── goals.html
├── resume.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/        ← add your photos here
└── downloads/     ← add your resume PDFs here
```

### 3. Enable GitHub Pages
Go to your repo → Settings → Pages → Source: Deploy from branch → Branch: main → / (root)

Your site will be live at: `https://YOUR_USERNAME.github.io`

---

## Customizing

### Add photos
- `images/headshot.jpg` → used on the home page hero
- `images/about.jpg` → used on the About page sidebar

Then replace the placeholder divs in `index.html` and `about.html`:
```html
<!-- Replace this placeholder block: -->
<div class="frame-img">
  <span>📸</span>
  ...
</div>

<!-- With this: -->
<div class="frame-img">
  <img src="images/headshot.jpg" alt="Emma Xuan">
</div>
```

### Add resume PDFs for download
Place your PDFs in a `downloads/` folder:
- `downloads/Emma_Xuan_Cyber_Resume.pdf`
- `downloads/Emma_Xuan_CS_Resume.pdf`

Then uncomment the download links in `resume.html`.

### Update social links
Search for `YOUR_LINKEDIN` and `YOUR_GITHUB` in all HTML files and replace with your actual URLs.

---

## Structure
| Page | File | Content |
|------|------|---------|
| Home | `index.html` | Hero, stats, featured projects |
| About | `about.html` | Bio, skills, background |
| Projects | `projects.html` | All 6 projects in detail |
| Goals | `goals.html` | Career timeline and aspirations |
| Resume | `resume.html` | Both resume versions with download |
