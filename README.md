# Deepankar Shokeen - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a dark theme with cyan accents, smooth animations, and mobile-first design.

## 🚀 Features

- **Modern Dark Theme**: Sleek dark design with cyan (#00d4ff) accents
- **Responsive Design**: Fully responsive across all devices
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Beautiful project cards with links
- **Skills Display**: Organized skills by category
- **Education Timeline**: Timeline-style education section
- **Smooth Scrolling**: Smooth navigation between sections

## 📁 File Structure

```
resume/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization

### Personal Information
Edit the following sections in `index.html`:

1. **Hero Section** (lines 60-70):
   - Update name, title, and description
   - Modify the profile placeholder

2. **About Section** (lines 85-105):
   - Update personal description
   - Modify statistics (years experience, projects, technologies)

3. **Skills Section** (lines 110-170):
   - Add/remove skill categories
   - Update skill items with appropriate icons

4. **Education Section** (lines 175-200):
   - Update education details
   - Add more education items as needed

5. **Projects Section** (lines 205-280):
   - Update project details
   - Add your actual GitHub links
   - Include live demo links

6. **Contact Section** (lines 285-340):
   - Update contact information
   - Add your social media links

### Styling
Modify `styles.css` to customize:

- **Colors**: Change the cyan accent color (#00d4ff) to your preferred color
- **Fonts**: Update the Google Fonts import and font-family
- **Layout**: Adjust spacing, padding, and grid layouts
- **Animations**: Modify animation durations and effects

### Functionality
Edit `script.js` to customize:

- **Form handling**: Connect to a backend service
- **Animations**: Adjust animation timing and effects
- **Navigation**: Modify scroll behavior and active states

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter font family)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🚀 Getting Started

1. **Clone or download** the files to your local machine
2. **Open `index.html`** in your web browser
3. **Customize** the content as described above
4. **Deploy** to your preferred hosting service

## 🌐 Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Upload your files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your folder to Netlify
2. Your site will be live instantly
3. Customize domain if needed

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## 📝 Customization Tips

### Adding Your Photo
Replace the profile placeholder in the hero section:
```html
<div class="profile-placeholder">
    <img src="path/to/your/photo.jpg" alt="Your Name" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
</div>
```

### Adding More Projects
Copy the project card structure and update:
```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" target="_blank" class="project-link">
                <i class="fab fa-github"></i>
                View Code
            </a>
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i>
                Live Demo
            </a>
        </div>
    </div>
</div>
```

### Changing Colors
Update the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #00d4ff;
    --secondary-color: #0099cc;
    --background-dark: #0a0a0a;
    --background-light: #111111;
    --text-primary: #ffffff;
    --text-secondary: #cccccc;
}
```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them with the community!

## 📞 Support

If you need help customizing your portfolio or have questions, feel free to reach out!

---

**Happy coding! 🚀** 