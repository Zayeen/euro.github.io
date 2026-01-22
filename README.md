# EURO IoT Intelligence

A Jekyll-powered blog exploring IoT security, smart home technology, and the future of connected devices.

## 🚀 Features

- **Jekyll Static Site Generator** - Fast, secure, and SEO-friendly
- **Blog Posts with Tags** - Organized content with tag system
- **Responsive Design** - Works perfectly on all devices
- **Creative Modern Styling** - Gradient accents, smooth animations, and clean typography
- **GitHub Pages Ready** - Automatic deployment on push

## 📁 Project Structure

```
euro.github.io/
├── _config.yml              # Jekyll configuration
├── _layouts/                # Page templates
│   └── default.html        # Base layout
├── _posts/                 # Blog posts (Markdown)
│   ├── 2026-01-20-ai-cameras-next-gen-surveillance.md
│   ├── 2026-01-19-matter-protocol-universal-translator.md
│   ├── 2026-01-18-biometrics-vs-keys.md
│   ├── 2026-01-17-data-encryption-living-room.md
│   ├── 2026-01-16-smart-grids-home-batteries.md
│   └── 2026-01-15-ambient-computing-invisible-tech.md
├── assets/
│   └── css/
│       └── main.css        # Styles
├── index.html              # Landing page
├── about.html              # About page
└── Gemfile                 # Ruby dependencies
```

## 🛠️ Local Development (Optional)

To test the site locally before pushing to GitHub:

1. **Install Ruby and Jekyll** (if not already installed)
   ```bash
   # Install Ruby from https://rubyinstaller.org/ (Windows)
   # Or use your system's package manager
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run local server**
   ```bash
   bundle exec jekyll serve
   ```

4. **View site**
   Open browser to `http://localhost:4000/euro.github.io/`

## 📝 Adding New Blog Posts

1. Create a new file in `_posts/` folder with format: `YYYY-MM-DD-title-slug.md`

2. Add front matter at the top:
   ```yaml
   ---
   layout: default
   title: "Your Post Title"
   date: 2026-01-22
   tags: [tag1, tag2, tag3]
   excerpt: "Short description of your post"
   ---
   ```

3. Write your content in HTML (inside `<div class="post-content">` wrapper)

4. Commit and push - site will automatically update!

## 🚀 Deployment

The site automatically deploys via **GitHub Pages** when you push to the repository.

1. **Commit your changes**
   ```bash
   git add .
   git commit -m "Update site"
   ```

2. **Push to GitHub**
   ```bash
   git push origin main
   ```

3. **View your site**
   Site will be live at: `https://zayeen.github.io/euro.github.io/`

GitHub Pages will automatically build and deploy your Jekyll site.

## 🎨 Customization

### Colors
Edit CSS variables in `assets/css/main.css`:
```css
:root {
    --primary: #6366f1;
    --secondary: #8b5cf6;
    --accent: #ec4899;
    /* ... more variables */
}
```

### Site Info
Edit `_config.yml`:
```yaml
title: Your Site Title
description: Your site description
author: Your Name
email: your-email@example.com
```

### Navigation
Edit links in `_layouts/default.html` header section.

## 📦 Future Enhancements

Easily add these features later:

- **Search** (30 min) - Lunr.js client-side search
- **Comments** (15 min) - utterances (GitHub Issues-based)
- **Portfolio Section** (1 hour) - Showcase projects
- **Tag Filtering** (30 min) - JavaScript tag filter
- **Dark Mode Toggle** (20 min) - Theme switcher

## � License

© 2026 EURO IoT Intelligence. All rights reserved.

## 🔗 Links

- **Repository**: https://github.com/Zayeen/euro.github.io
- **Live Site**: https://zayeen.github.io/euro.github.io/

---

Built with Jekyll • Hosted on GitHub Pages • Designed for security and intelligence
