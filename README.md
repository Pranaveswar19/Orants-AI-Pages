# Orants AI - AI Solutions Website

Professional website showcasing AI technology solutions with modern design.

## 📁 Project Structure

```
orants-ai-pages/
├── index.html              # Home page
├── chatbots-rag.html       # Custom Chatbots & RAG Systems
├── ai-healthcare.html      # AI for Healthcare
├── quantum-ai.html         # Quantum AI Research
├── llamaindex.html         # LlamaIndex Technology
└── css/
    └── style.css           # Global styles
```

## 🚀 Running Locally

### Option 1: Direct Browser
1. Clone the repository
2. Open `index.html` in your browser

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server -p 8000
```

Then visit: `http://localhost:8000`

## 🌐 Deploy to Vercel

### Via GitHub (Recommended)
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Click "Deploy"

### Via Vercel CLI
```bash
npm install -g vercel
vercel login
vercel --prod
```

## 📝 Admin Content Updates

### Update Statistics (Admin Only)

Statistics use placeholder format for easy customization:
- `[Number]` - Replace with numeric values
- `[Percentage]` - Replace with percentage values
- `[Metric Label]` - Replace with metric descriptions

**How to update:**
1. Open the HTML file you want to edit
2. Search for placeholders (e.g., `[Number]`)
3. Replace with your actual data
4. Save and commit changes
5. Redeploy to see updates

### Update Call-to-Action Buttons (Admin Only)

**Location of CTA buttons:**
- Navigation: Line with `class="nav-cta"`
- Hero sections: Lines with `class="btn-primary"` or `class="btn-secondary"`
- Footer CTAs: Lines with `class="cta-section"`

**To modify button text/links:**
1. Open the HTML file in a text editor
2. Find: `<a href="#contact" class="btn-primary">Button Text</a>`
3. Change `href` attribute for the link destination
4. Change text between tags for button label
5. Save file and commit
6. Push to GitHub and redeploy

**Example:**
```html
<!-- Before -->
<a href="#contact" class="btn-primary">Request Demo</a>

<!-- After -->
<a href="https://calendly.com/yourlink" class="btn-primary">Book Consultation</a>
```

### Update Navigation Links (Admin Only)

Edit navigation in all HTML files:
```html
<nav>
    <div class="nav-container">
        <a href="index.html" class="logo">Orants <span>AI</span></a>
        <ul class="nav-links">
            <li><a href="index.html">Home</a></li>
            <li><a href="chatbots-rag.html">AI Solutions</a></li>
            <!-- Modify or add links here -->
        </ul>
        <a href="#contact" class="nav-cta">Request Demo</a>
    </div>
</nav>
```

**Note:** Update navigation in all 5 HTML files to maintain consistency.

### Update Company Information (Admin Only)

**Footer section** appears at bottom of each page:
```html
<footer>
    <div class="footer-content">
        <div class="footer-section">
            <h3>Orants AI</h3>
            <p>Innovating the future with intelligent solutions</p>
        </div>
    </div>
    <div class="footer-bottom">
        <p>&copy; 2024 Orants AI. All rights reserved.</p>
    </div>
</footer>
```

Update the tagline and copyright year in all HTML files.

## 🎨 Design Customization (Admin Only)

### Colors
Edit `css/style.css` to change theme colors:
```css
:root {
    --primary-bg: #0a0a0f;        /* Main background */
    --accent-cyan: #00d9ff;       /* Accent color */
    --text-primary: #ffffff;      /* Main text */
}
```

### Typography
Modify font settings in `css/style.css`:
```css
body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto;
}
```

## 🔄 Deployment Workflow (Admin Only)

After making changes:
```bash
git add .
git commit -m "Update: [describe your changes]"
git push origin main
```

Vercel will automatically redeploy your site.

## 🔧 Technical Details

- **Framework:** Pure HTML5 & CSS3
- **Dependencies:** None
- **Build Process:** Not required
- **Browser Support:** All modern browsers

## 📄 License

All rights reserved © 2024 Orants AI
