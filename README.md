# Video Editor Portfolio Website

A modern, responsive portfolio website designed for video editors to showcase their work with YouTube and Instagram embeds.

## Features

- 🎬 **Modern Design** - Clean, dark theme with gradient accents
- 📱 **Fully Responsive** - Works on all devices (desktop, tablet, mobile)
- 🎨 **YouTube & Instagram Embeds** - Easily showcase your video content
- 🔍 **Portfolio Filtering** - Filter projects by category (YouTube, Instagram, Commercial)
- ✨ **Smooth Animations** - Fade-in effects and hover animations
- 📧 **Contact Form** - Built-in contact form for client inquiries
- 🚀 **GitHub Pages Ready** - Easy deployment to GitHub Pages

## Quick Start

### 1. Customize Your Content

Open `index.html` and replace the placeholder content:

- **Your Name**: Replace "YourName" in the logo and title
- **Hero Section**: Update the headline and subtitle
- **Portfolio Items**: 
  - Replace YouTube video IDs in iframe `src` attributes
  - Replace Instagram post URLs in `data-instgrm-permalink` attributes
  - Update project titles and descriptions
- **About Section**: Add your experience and bio
- **Contact Info**: Update email and social media links

### 2. Add Your Videos

#### For YouTube Videos:
```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID"></iframe>
```

#### For Instagram Posts/Reels:
```html
<blockquote class="instagram-media" 
            data-instgrm-permalink="https://www.instagram.com/p/YOUR_POST_ID/">
</blockquote>
```

### 3. Deploy to GitHub Pages

#### Option A: Using Git Command Line

```bash
# Initialize git repository (if not already done)
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial portfolio website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git push -u origin main

# Enable GitHub Pages:
# 1. Go to your repository on GitHub
# 2. Click Settings > Pages
# 3. Select "main" branch and root folder
# 4. Click Save
```

#### Option B: Using GitHub Desktop

1. Open GitHub Desktop
2. Add your local repository
3. Commit changes
4. Publish to GitHub
5. Go to repository settings on GitHub
6. Enable GitHub Pages (Settings > Pages)

#### Option C: Direct Upload

1. Create a new repository on GitHub
2. Upload all files (index.html, styles.css, script.js)
3. Go to Settings > Pages
4. Select source branch (main/master) and root folder
5. Click Save

Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## File Structure

```
├── index.html      # Main HTML file
├── styles.css      # All styling and responsive design
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## Customization Tips

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;     /* Main accent color */
    --secondary-color: #ec4899;   /* Secondary accent */
    --bg-dark: #0f0f0f;           /* Background color */
}
```

### Adding More Projects
Copy a `.portfolio-item` div and update:
- `data-category` attribute for filtering
- Video embed URL
- Project title and description

### Contact Form
For a working contact form without backend, consider:
- [Formspree](https://formspree.io/)
- [Netlify Forms](https://www.netlify.com/products/forms/)
- [EmailJS](https://www.emailjs.com/)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

Free to use and modify for personal and commercial projects.

---

Made with ❤️ for video editors
