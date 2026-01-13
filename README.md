# Jake Schwartz - Personal Website

A modern, minimalist personal website showcasing my professional interests and career accomplishments in business and consulting.

## Overview

This website serves as a professional portfolio and online presence, highlighting my expertise in strategic planning, business analysis, and consulting. The site features a clean, responsive design optimized for all devices.

## Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, minimalist design with smooth animations and transitions
- **Professional Sections**:
  - Hero section with call-to-action
  - About section with core competencies
  - Career interests showcase
  - Contact section with resume download
- **Smooth Navigation**: Animated scrolling between sections
- **Performance Optimized**: Fast loading with vanilla JavaScript (no frameworks)

## Structure

```
Jake_Schwartz_Website/
├── index.html              # Main website file
├── Jake-Schwartz-Resume.pdf # Downloadable resume
└── README.md              # This file
```

## Getting Started

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Jake_Schwartz_Website.git
   cd Jake_Schwartz_Website
   ```

2. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server (recommended):
     ```bash
     python -m http.server 8000
     # or
     npx serve
     ```

3. Navigate to `http://localhost:8000` in your browser

### Deployment

This site can be easily deployed using:

- **GitHub Pages**:
  1. Go to repository Settings > Pages
  2. Select main branch as source
  3. Your site will be live at `https://yourusername.github.io/Jake_Schwartz_Website/`

- **Netlify**: Drag and drop the folder to Netlify for instant deployment

- **Vercel**: Connect your GitHub repository for automatic deployments

## Customization

To personalize the website for your needs:

1. **Update Contact Information** (in `index.html`):
   - Replace email address in the contact section
   - Update LinkedIn profile URL
   - Ensure resume PDF filename matches your file

2. **Modify Content**:
   - Edit the about section text to reflect your background
   - Update core competencies list with your skills
   - Customize career interests cards with your focus areas

3. **Adjust Colors** (CSS variables in `<style>` section):
   ```css
   --primary-color: #2c3e50;
   --accent-color: #3498db;
   ```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript**: Vanilla JS for smooth interactions
- **No Dependencies**: Pure frontend code, no build process required

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

## Contact

For inquiries or opportunities, please reach out through the contact section on the website.

---

**Built with** dedication to clean code and modern web design principles.
