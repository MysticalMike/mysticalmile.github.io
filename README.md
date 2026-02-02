# Portfolio Website

A clean, minimalist, and professional portfolio website built with vanilla HTML, CSS, and JavaScript. Fully optimized for GitHub Pages deployment.

![Portfolio Desktop View](https://github.com/user-attachments/assets/f508d78c-7f6a-4af8-8e43-5cbe7620893c)

## ✨ Features

- **Clean & Minimalist Design**: Professional aesthetic with a neutral color scheme and blue accents
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Interactions**: Smooth scrolling, hover effects, and animated transitions
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Projects Showcase**: Display your projects with descriptions, tech stacks, and links
- **Contact Section**: Easy-to-update contact information with email and social links
- **GitHub Pages Ready**: Deploy instantly to GitHub Pages with zero configuration
- **Fast Loading**: Optimized performance with no dependencies

## 🚀 Quick Start

### 1. Customize Your Information

#### Edit `index.html`

**Hero Section** (Lines 26-33):
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<p class="hero-subtitle">Full Stack Developer</p>
<p class="hero-description">I build elegant and efficient solutions to complex problems.</p>
```

**About Section** (Lines 39-48):
- Update the introduction paragraphs
- Modify skill tags to match your skills

**Projects Section** (Lines 56-148):
- Update project titles, descriptions, and tech stacks
- Replace `#` in links with your actual project URLs
- Add or remove projects by copying/pasting the `<article class="project-card">` blocks

**Contact Section** (Lines 154-176):
- Update email address
- Update GitHub username
- Update LinkedIn profile URL

### 2. Customize Colors (Optional)

Edit the CSS variables in `styles.css` (Lines 11-18):

```css
--color-primary: #2563eb;        /* Main accent color */
--color-primary-dark: #1e40af;   /* Darker accent for hovers */
--color-accent: #10b981;         /* Secondary accent color */
```

### 3. Deploy to GitHub Pages

1. Push your changes to GitHub:
   ```bash
   git add .
   git commit -m "Customize portfolio"
   git push origin main
   ```

2. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under "Source", select **main** branch
   - Click **Save**

3. Your site will be live at: `https://yourusername.github.io/portfolio/`

## 📁 File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styles and responsive design
├── script.js       # JavaScript for interactions
└── README.md       # This file
```

## 🎨 Customization Guide

### Adding More Projects

Copy this block and paste it in the `projects-grid` section:

```html
<article class="project-card">
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Description of your project.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://your-demo-link.com" class="project-link" target="_blank">
                <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path>
                    <polyline points="15 3 21 3 21 9"></polyline>
                    <line x1="10" y1="14" x2="21" y2="3"></line>
                </svg>
                Live Demo
            </a>
            <a href="https://github.com/yourusername/repo" class="project-link" target="_blank">
                <svg class="icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                    <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path>
                </svg>
                GitHub
            </a>
        </div>
    </div>
</article>
```

### Changing the Color Scheme

The portfolio uses CSS custom properties (variables) for easy theming. All colors are defined at the top of `styles.css`:

- **Professional Blue** (default): `#2563eb`
- **For Green accent**: Change to `#10b981`
- **For Purple accent**: Change to `#8b5cf6`
- **For Orange accent**: Change to `#f97316`

### Adding More Skills

In the About section, add more skill tags:

```html
<span class="skill-tag">Your Skill</span>
```

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints at:
- **Desktop**: 1200px and above (full layout)
- **Tablet**: 768px - 1199px (adapted grid)
- **Mobile**: Below 768px (stacked layout with hamburger menu)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 License

This project is open source and available under the MIT License. Feel free to use it for your own portfolio!

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you have suggestions for improvements, please open an issue or submit a pull request.

## 📸 Screenshots

### Desktop View
![Desktop Full Page](https://github.com/user-attachments/assets/f508d78c-7f6a-4af8-8e43-5cbe7620893c)

### Mobile View
![Mobile View](https://github.com/user-attachments/assets/83631784-5afe-46cd-8e3c-5f094a09cd9f)

### Mobile Menu
![Mobile Menu](https://github.com/user-attachments/assets/8b8e3c74-06e3-4c21-9be1-82b410307aa8)

---

**Ready to deploy!** 🚀 Just customize with your information and push to GitHub Pages.
