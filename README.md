# Portfolio Website - Ravi Katariya

A modern, interactive, and visually stunning portfolio website showcasing my work as a Data Scientist & AI Engineer.

## Features

- **Modern Dark Theme**: Beautiful dark blue color scheme with bright blue accents
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Animations**: Smooth scroll animations, typewriter effects, and hover interactions
- **Sections Included**:
  - Hero section with animated introduction
  - About section with profile and statistics
  - Journey section (Education & Experience timeline)
  - Skills section with animated progress bars
  - Projects showcase with GitHub links
  - Achievements & Leadership section
  - Contact form with social media links

## Technologies Used

- HTML5
- CSS3 (with animations and transitions)
- JavaScript (Vanilla JS for interactivity)
- Font Awesome (for icons)
- Google Fonts (Poppins)

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process or dependencies required.

## Customization

### Updating Personal Information

Edit `index.html` to update:
- Name, title, and description in the hero section
- About section content
- Education and experience details
- Skills and percentages
- Project information
- Contact information

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-bg: #0a0e27;
    --secondary-bg: #0f1629;
    --accent-blue: #00d4ff;
    --accent-blue-dark: #0099cc;
    --text-white: #ffffff;
    --text-gray: #b8b8b8;
}
```

### Adding Projects

Add new project cards in the projects section:

```html
<div class="project-card" data-aos="fade-up">
    <div class="project-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3 class="project-title">Project Name</h3>
    <p class="project-date">Date</p>
    <p class="project-description">Description</p>
    <div class="project-tech">
        <span class="tech-tag">Technology</span>
    </div>
    <a href="github-link" target="_blank" class="project-link">
        View on GitHub <i class="fas fa-arrow-right"></i>
    </a>
</div>
```

## Deployment

### GitHub Pages (Automated)

This repository is configured with GitHub Actions for automatic deployment to GitHub Pages.

**Setup Instructions:**
1. Push your code to a GitHub repository (already done for this repo)
2. Go to your repository Settings > Pages
3. Under "Build and deployment", set Source to **GitHub Actions**
4. The site will automatically deploy on every push to the main branch
5. Your site will be live at `https://ravik04.github.io/Portfolio-ravi`

**Manual Deployment:**
Alternatively, you can manually deploy by:
1. Going to Settings > Pages
2. Select the main branch as source
3. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop your project folder to [Netlify](https://www.netlify.com/)
2. Your site will be deployed instantly

### Vercel

1. Import your GitHub repository to [Vercel](https://vercel.com/)
2. Deploy with zero configuration

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contact

- **Email**: ravikatariya138@gmail.com
- **Phone**: +91-7987984891
- **LinkedIn**: [ravi-katariya-576a45217](https://www.linkedin.com/in/ravi-katariya-576a45217/)
- **GitHub**: [ravik04](https://github.com/ravik04)

## License

This project is open source and available for personal use.
