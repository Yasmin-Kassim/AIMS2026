# AIMS 2026: AI for Multimodal Science Website

A modern, responsive static website for the AIMS 2026 workshop at UC San Diego.

## Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive**: Fully responsive layout that works on all devices
- **Easy to Customize**: Well-organized HTML, CSS, and JavaScript files
- **Fast Loading**: Lightweight static site with no dependencies
- **Accessible**: Semantic HTML and proper navigation structure

## File Structure

```
AIMS_website/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # Interactive features
└── README.md       # This file
```

## Customization Guide

### Updating Content

1. **Hero Section**: Edit the hero section in `index.html` (lines ~30-60)
   - Update title, subtitle, dates, and description

2. **About Section**: Modify the about content (lines ~65-100)
   - Update workshop description
   - Add/modify topics and format lists

3. **Schedule**: Update the schedule section (lines ~105-220)
   - Modify times, events, and descriptions for each day
   - Add or remove schedule items as needed

4. **Speakers**: Edit the speakers section (lines ~225-260)
   - Replace placeholder speaker cards with actual speaker information
   - Add speaker photos by replacing the SVG icons
   - Update speaker names and titles

5. **Venue**: Modify venue information (lines ~265-300)
   - Update specific building/room details when available
   - Add actual map embed if desired

6. **Organizers**: Update organizing committee (lines ~305-330)
   - Add organizer names and affiliations
   - Replace placeholder cards

7. **Contact**: Update contact information (lines ~335-365)
   - Change email address
   - Update phone number
   - Add additional contact methods if needed

### Styling

- **Colors**: Modify CSS variables in `styles.css` (lines ~8-16)
  - Primary color: `--primary-color` (UCSD blue)
  - Secondary color: `--secondary-color` (UCSD gold)
  - Adjust other colors as needed

- **Fonts**: Currently using Inter font from Google Fonts
  - Change in `index.html` head section if desired

### Adding Images

To add speaker photos or other images:

1. Create an `images` folder in the project directory
2. Add your image files
3. Replace the SVG icons in speaker/organizer cards with:
   ```html
   <img src="images/speaker-name.jpg" alt="Speaker Name">
   ```
4. Update CSS for `.speaker-avatar` or `.organizer-avatar` to remove background and adjust sizing

### Adding a Map

To embed a Google Map or other map service:

1. Get embed code from Google Maps or your preferred service
2. Replace the `.map-placeholder` div in the venue section with the embed iframe

## Deployment

This is a static website that can be deployed to:

- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **Netlify**: Drag and drop the folder or connect a Git repository
- **Vercel**: Import the project and deploy
- **Any web hosting service**: Upload files via FTP

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- The website uses no external dependencies except Google Fonts
- All animations are CSS-based for performance
- The site is optimized for fast loading
- Mobile navigation menu is included for smaller screens

## Future Enhancements

Consider adding:
- Actual speaker photos and bios
- Detailed schedule with abstracts
- Registration form (if needed later)
- Social media links
- Photo gallery
- Archive of past workshops



