# REDLINE STUDIOS - Game Landing Page

A professional, responsive landing page for your game built with HTML, CSS, and JavaScript.

## Features

✨ **Modern Design**
- Clean, professional layout with smooth animations
- Fully responsive for desktop, tablet, and mobile devices
- Dark theme with red accents matching the REDLINE STUDIOS brand

🎮 **Sections**
- **Hero Section** - Eye-catching banner with call-to-action buttons
- **About** - Game description with feature highlights
- **Gallery** - Screenshot and media showcase
- **Contact** - Message form for user inquiries
- **Navigation** - Sticky navbar with smooth scrolling

⚡ **Interactive Elements**
- Smooth scroll navigation
- Button hover effects
- Contact form with validation
- Responsive gallery grid
- Active navigation indicators

## File Structure

```
.
├── index.html      # Main HTML structure
├── styles.css      # Styling and layouts
├── script.js       # JavaScript interactivity
└── README.md       # This file
```

## Getting Started

### Local Development

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/sadasivjha456-rgb/REDLINE-STUDIOS-.git
   cd REDLINE-STUDIOS-
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     
     # Node.js (using http-server)
     npx http-server
     ```

3. **Visit** `http://localhost:8000` in your browser

## Deploy with GitHub Pages

1. Go to your repository settings
2. Scroll to **GitHub Pages** section
3. Select `main` branch as source
4. Save and your site will be live at: `https://sadasivjha456-rgb.github.io/REDLINE-STUDIOS-/`

## Customization

### Update Game Information

Edit `index.html`:
- Change game title and description in the About section
- Update feature highlights in the feature cards
- Modify social links in the footer

### Change Colors

Edit `styles.css` and modify the CSS variables at the top:
```css
:root {
    --primary-color: #e74c3c;        /* Red accent */
    --secondary-color: #2c3e50;      /* Dark blue */
    --accent-color: #3498db;         /* Light blue */
    --light-bg: #ecf0f1;             /* Light background */
    --dark-bg: #1a1a1a;              /* Dark background */
}
```

### Add Screenshots

Replace placeholder gallery items:
1. Replace `<div class="placeholder">Screenshot X</div>` with:
   ```html
   <img src="path/to/screenshot.png" alt="Screenshot Description">
   ```
2. Adjust image sizes in `styles.css` as needed

### Contact Form Integration

The form currently shows alerts. To save submissions, integrate with:
- **FormSubmit** - Free form backend service
- **Formspree** - Simple form submissions
- **Firebase** - Backend database
- **Custom backend** - Your own server

## Next Steps

1. **Add screenshots** - Replace gallery placeholders with game images
2. **Customize content** - Update game title, description, and features
3. **Add game download** - Link "Play Now" button to game
4. **Integrate contact form** - Set up backend for messages
5. **Social media links** - Update footer with your channels
6. **Add favicon** - Branding in browser tab

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (Vanilla)** - No dependencies, pure JS for interactivity

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## License

This project is open source and available under the MIT License.

---

**Built with ❤️ by REDLINE STUDIOS**
