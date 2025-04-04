# Center of Excellence Human-Centered Computing Landing Page

This is a responsive landing page for the Center of Excellence Human-Centered Computing, designed to closely match the SolarOne WordPress theme layout and design patterns.

## Overview

This landing page implements a professional design inspired by the SolarOne WordPress block theme, featuring:

- Grid-based layout system matching the SolarOne theme structure
- Professional design with authentic SolarOne images and styling
- Responsive design with mobile-first approach
- 12-column grid system for precise content alignment
- Sections for hero, about, services, testimonials, and contact

## File Structure

- `index.html` - The main HTML structure with SolarOne-style grid layout
- `styles.css` - CSS with grid system and styling matching SolarOne aesthetics
- `README.md` - This documentation file

## Key Design Features

### Grid System
The landing page implements a 12-column grid system identical to SolarOne's layout:
- Uses `alignfull` for full-width sections
- Uses `alignwide` for contained content
- Grid columns are defined with precise start and end points for perfect alignment

### Visual Elements
- Authentic SolarOne images and icons
- Consistent spacing and typography 
- Original color scheme matching SolarOne
- Testimonial layout with accurate styling

## How to Use

1. Download or clone all files to your web server or local environment
2. Open `index.html` in a web browser to view the page
3. The page is fully responsive and will adapt to different screen sizes

## Customization

### Modifying the Grid Layout

The grid system uses CSS Grid with specific column positioning:

```css
.grid-item {
    grid-column-start: 2;
    grid-column-end: 6;
}
```

Adjust these values to change content positioning across the 12-column grid.

### Changing Colors

The color scheme is defined using CSS variables at the top of the `styles.css` file:

```css
:root {
    --color-primary: #044FE7;
    --color-secondary: #00B6AF;
    --color-tertiary: #7761FF;
    /* Additional color variables... */
}
```

### Images

The landing page uses actual SolarOne theme images. If you want to replace them:

```html
<img src="path/to/your/image.jpg" alt="Description">
```

## Browser Compatibility

This landing page works in all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Credits

- Design structure directly inspired by SolarOne WordPress theme
- Images sourced from the SolarOne theme
- Inter font by Google Fonts

## License

This landing page template is free to use for both personal and commercial projects.

---

Developed for the Center of Excellence Human-Centered Computing 