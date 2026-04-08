# OFGEN Website Replica

A modern, responsive replica of the OFGEN website (https://ofgen.netlify.app/) built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI**: Clean, professional corporate design with smooth animations
- **Interactive Navigation**: Sticky header with smooth scrolling and mobile menu
- **Content Sections**: All original content including About, Capabilities, Projects, Team, and Contact
- **Performance Optimized**: Lazy loading, debounced scroll events, and efficient animations
- **Accessibility**: Semantic HTML5 structure with proper heading hierarchy

## File Structure

```
ofgenweb/
├── index.html      # Main HTML structure
├── styles.css      # Complete styling with responsive design
├── script.js       # Interactive JavaScript functionality
└── README.md       # This file
```

## Getting Started

### Option 1: Direct Opening
Simply open `index.html` in your web browser. The website will work perfectly without any server setup.

### Option 2: Local Server (Recommended for development)
If you have Python installed:
```bash
python -m http.server 8000
```

Then navigate to `http://localhost:8000` in your browser.

## Website Sections

1. **Navigation**: Fixed header with smooth scroll navigation
2. **Hero**: Main landing section with company tagline
3. **About**: Company overview and statistics
4. **Vision & Values**: Mission, footprint, strategy, and core values
5. **Capabilities**: Developer, Infrastructure Investor, and EPC services
6. **Team**: Board of Directors and Executive Management
7. **Projects**: Active pipeline with case studies
8. **Contact**: Regional offices and contact information

## Technical Features

- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Variables**: Consistent theming
- **Intersection Observer**: Scroll-triggered animations
- **Debouncing**: Optimized scroll performance
- **Mobile-First**: Responsive design approach
- **Print Styles**: Optimized for printing

## Browser Compatibility

- Chrome/Chromium 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Customization

The website is built with modularity in mind. You can easily:
- Update colors by modifying CSS variables
- Add new projects by duplicating project cards
- Modify content directly in HTML
- Extend JavaScript functionality

## Performance

- Optimized images (when added)
- Minimal external dependencies
- Efficient CSS animations
- Lazy loading support
- Print-friendly design

## Notes

- Font: Inter (loaded from Google Fonts)
- Color scheme: Professional blue (#0066cc) with neutral grays
- Animations: Subtle fade-in and hover effects
- Mobile menu: Hamburger navigation for small screens
