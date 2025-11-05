# fnrt UI Theme

A modern, responsive dashboard theme built with HTML, Tailwind CSS, and JavaScript.

## Project Structure

```
theme-shadcn-html/
├── index.html          # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css  # Custom CSS styles
│   ├── js/
│   │   └── script.js   # JavaScript functionality
│   └── images/         # Image assets (if any)
└── README.md           # This file
```

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between dark and light themes
- **Collapsible Sidebar**: Sidebar can be collapsed/expanded with smooth animations
- **Hover to Expand**: Collapsed sidebar expands on hover
- **Notifications System**: Dropdown notifications with badges
- **Interactive Charts**: Using Chart.js for data visualization
- **Modern UI**: Clean, professional design with Tailwind CSS

## Quick Start

1. Clone or download the project
2. Open `index.html` in your web browser
3. The theme is ready to use!

## Customization

### Colors
The theme uses Tailwind CSS classes. You can customize colors by modifying the Tailwind config in `index.html`:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                // Your custom colors here
            }
        }
    }
}
```

### Layout
- Main layout is in `index.html`
- Custom styles are in `assets/css/styles.css`
- JavaScript functionality is in `assets/js/script.js`

### Adding New Pages
1. Create new HTML files in the root directory
2. Copy the basic structure from `index.html`
3. Include the necessary CSS and JS files

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Dependencies

- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Chart.js](https://www.chartjs.org/) - Simple yet flexible JavaScript charting
- [Lucide](https://lucide.dev/) - Beautiful & consistent icon toolkit

## Development

To modify the theme:

1. Edit `index.html` for structure changes
2. Edit `assets/css/styles.css` for custom styles
3. Edit `assets/js/script.js` for functionality changes
4. Test in multiple browsers

## License

This theme is free to use for personal and commercial projects.