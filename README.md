# Sohel Akhtar - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a CSE-AI student and aspiring AI Engineer.

## 🌟 Features

- **Responsive Design**: Fully mobile-friendly with adaptive layouts
- **Dark Theme**: Modern dark gradient background with futuristic UI elements
- **Interactive Elements**: 
  - Animated skill carousel
  - Smooth scrolling navigation
  - Hover effects and transitions
  - Floating animated numbers
  - Glowing code overlay effects
- **Contact Form**: Functional contact form with Google Sheets integration
- **Social Links**: Direct links to LinkedIn, Instagram, Facebook, and phone
- **Project Showcase**: Detailed project descriptions with external links
- **AOS Animations**: Scroll-triggered animations for enhanced UX

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS (CDN)
- **Animations**: AOS (Animate On Scroll)
- **Icons**: SVG icons and custom graphics
- **Form Handling**: Google Apps Script for contact form
- **Responsive Design**: CSS Media Queries + Tailwind responsive classes

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Open the project**
   - Simply open `portfolio.html` in your web browser
   - Or use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (if you have live-server installed)
     npx live-server
     
     # Using VS Code Live Server extension
     # Right-click on portfolio.html and select "Open with Live Server"
     ```

3. **Customize the content**
   - Edit `portfolio.html` to update your personal information
   - Replace images in the root directory
   - Update social media links
   - Modify the contact form endpoint if needed

## 📁 Project Structure

```
portfolio/
├── portfolio.html          # Main HTML file
├── README.md              # This file
├── package.json           # Node.js dependencies
├── Sohel Akhtar CV.pdf    # Resume file
├── Virtual Herbal Garden.pptx.pdf  # Project presentation
├── 360_F_496711575_BgcZue87HzqNe8JxoGm9F1UiSgZAnE55-Photoroom.png  # Instagram icon
├── facebook.png           # Facebook icon
├── linkedin-logo.png      # LinkedIn icon
├── phone-call.png         # Phone icon
├── python.png             # Python icon
└── mesmerizing-scenery-green-mountains-with-cloudy-sky-surface.jpg  # Background image
```

## 🎨 Customization

### Colors and Theme
The website uses a dark theme with:
- Primary gradient: Deep navy to black
- Accent colors: Blue (#3b82f6) and Purple (#8b5cf6)
- Text colors: Light gray (#e0e6f0)

### Sections
1. **Home**: Hero section with introduction
2. **About**: Personal background and goals
3. **Skills**: Interactive carousel of technical skills
4. **Projects**: Showcase of completed projects
5. **Experience**: Work and volunteer experience
6. **Achievements**: Awards and recognitions
7. **Contact**: Contact form and social links

### Adding New Projects
To add a new project, duplicate the project card structure:
```html
<div class="project-card glass-card">
  <h3 class="text-xl font-bold mb-3">Project Title</h3>
  <p class="text-lg mb-4">Project description goes here.</p>
  <a href="project-link" target="_blank" class="text-blue-400 hover:text-blue-300 transition">View Project →</a>
</div>
```

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

Key responsive features:
- Mobile hamburger menu
- Adaptive font sizes
- Flexible grid layouts
- Touch-friendly buttons

## 🔧 Configuration

### Contact Form
The contact form uses Google Apps Script. To set up your own:
1. Create a new Google Sheet
2. Go to Extensions > Apps Script
3. Replace the script with the form handler code
4. Deploy as a web app
5. Update the form action URL in `portfolio.html`

### Social Links
Update the social media links in the contact section:
```html
<a href="your-linkedin-url" target="_blank">LinkedIn</a>
<a href="your-instagram-url" target="_blank">Instagram</a>
<!-- etc. -->
```

## 🌐 Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty for static sites)
3. Set publish directory: (root directory)
4. Deploy automatically on push

### Vercel
1. Import your GitHub repository
2. Vercel will auto-detect it as a static site
3. Deploy with one click

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions, please open an issue.

## 📞 Contact

- **LinkedIn**: [Sohel Akhtar](https://www.linkedin.com/in/sohel-akhtar-26b901260)
- **Instagram**: [@sx_hell_](https://www.instagram.com/sx_hell_?igsh=MXB0cnloZ2RjZnNkaQ==)
- **Facebook**: [Sohel Akhtar](https://www.facebook.com/share/1GErdJkTbA/)
- **Phone**: +91 9678097461

---

⭐ **Star this repository if you found it helpful!** 