# Path Consulting Website

A professional, BCG/McKinsey-style website for Path Consulting - a student-led consulting organization at Claremont McKenna College that partners with local governments and civic institutions to strengthen democracy at the community level.

## Overview

This website showcases Path Consulting's mission, projects, expertise, and partners through a modern, responsive design that emphasizes professionalism and civic impact.

## Features

### Design
- **Color Palette**: Maroon (#800020), Black, White, with gray accents
- **Typography**: Inter for body text, Montserrat for headings
- **Animations**: Smooth scroll-based animations using AOS (Animate On Scroll)
- **Responsive**: Fully responsive design with breakpoints for mobile, tablet, and desktop

### Sections

1. **Navigation Bar**: Sticky header with smooth scroll navigation and mobile hamburger menu
2. **Hero Section**: Impactful headline with stats showcasing 25+ consultants, 15+ projects, 10+ partners
3. **Who We Are**: Two-column layout introducing Path Consulting and listing key clients
4. **Our Mission**: Maroon background section highlighting the mission to build resilient local institutions
5. **Why We Do What We Do**: Three-column cards featuring Local Impact, Student Excellence, and Democratic Resilience
6. **Featured Projects**: Grid of four major projects with tags and descriptions:
   - Election Systems Analysis
   - Supportive Housing Strategy
   - Tiny Homes Feasibility Study
   - Transit Infrastructure Analysis
7. **Our Expertise**: Eight key areas of expertise displayed in a clean grid
8. **Our Partners**: Showcase of trusted civic institutions and local governments
9. **Call-to-Action**: Contact section with email link
10. **Footer**: Multi-column layout with quick links, contact info, and social media

## Technical Stack

- **Framework**: React 18 (via CDN)
- **Styling**: Tailwind CSS (via CDN)
- **Animations**: AOS (Animate On Scroll) library
- **Typography**: Google Fonts (Inter + Montserrat)
- **Build**: Single HTML file - no build process required

## Setup & Deployment

### Local Development

1. Clone the repository
2. Open `index.html` in your browser
3. No build process required - it's a static site!

### GitHub Pages Deployment

This site is configured for GitHub Pages deployment:
- The `CNAME` file points to `www.cmcpath.com`
- Simply push to the main branch and GitHub Pages will serve the site

### Files

```
PathWebsite/
├── index.html          # Main website file
├── pathLogo.png        # Path Consulting logo
├── CNAME              # Custom domain configuration
└── README.md          # This file
```

## Performance Optimizations

- ✅ Lazy loading for animations
- ✅ Optimized images
- ✅ Minimal external dependencies
- ✅ Smooth scroll behavior
- ✅ Fast load times (<3 seconds)

## Accessibility Features

- ✅ Semantic HTML structure
- ✅ Alt text for images
- ✅ Keyboard navigation support
- ✅ High color contrast ratios
- ✅ Responsive touch targets for mobile

## SEO Optimization

- ✅ Meta tags for social sharing (Open Graph + Twitter Cards)
- ✅ Descriptive page title and meta description
- ✅ Canonical URL
- ✅ Proper heading hierarchy
- ✅ Semantic HTML

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Updating Content

All content is defined in JavaScript objects within `index.html`:

- **Stats**: Lines 218-222
- **Why Cards**: Lines 224-240
- **Projects**: Lines 242-271
- **Expertise Areas**: Lines 273-282
- **Partners**: Lines 284-290

### Changing Colors

Update the Tailwind configuration (lines 47-65) to modify the color scheme:

```javascript
colors: {
  maroon: {
    DEFAULT: '#800020',  // Change these hex values
    dark: '#600000',
    light: '#9B0026'
  }
}
```

### Adding Sections

1. Add a new section with a unique `id` attribute
2. Add the section ID to `navItems` array
3. Update the scroll tracking in the `handleScroll` function

## Contact

For questions or support:
- **Email**: pathconsulting@claremont.edu
- **Website**: https://www.cmcpath.com

## License

© 2025 Path Consulting | Claremont McKenna College. All rights reserved.
