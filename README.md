# Savni Goyal - Photography Portfolio Website

A modern, fully responsive photography portfolio website built with HTML, CSS, and JavaScript.

## Features

### 🎨 Design & UI
- **Modern Design**: Clean, professional aesthetic with beautiful typography
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Mobile-First**: Designed with mobile compatibility as a priority
- **Smooth Animations**: CSS animations and transitions for enhanced user experience
- **Professional Color Scheme**: Elegant gradient backgrounds and consistent branding

### 📱 Mobile Compatibility
- **Responsive Navigation**: Hamburger menu for mobile devices
- **Touch-Friendly**: Large touch targets and swipe gestures
- **Mobile-Optimized Layout**: Grid layouts that adapt to screen size
- **Fast Loading**: Optimized images and lazy loading

### 🖼️ Portfolio Features
- **Image Gallery**: Beautiful grid layout showcasing photography work
- **Category Filtering**: Filter images by category (Portraits, Landscapes, Events)
- **Lightbox Viewer**: Full-screen image viewing with navigation
- **Keyboard Navigation**: Arrow keys and ESC support in lightbox
- **Swipe Gestures**: Touch swipe support for mobile lightbox navigation

### 📧 Contact & Interaction
- **Contact Form**: Functional contact form with EmailJS integration
- **Email Integration**: Direct email sending via EmailJS service
- **Form Validation**: Real-time validation with user feedback
- **Social Media Links**: Easy access to social profiles
- **Professional Information**: Clear contact details and location info

### ⚡ Performance & Accessibility
- **Fast Loading**: Optimized CSS and JavaScript
- **Lazy Loading**: Images load as needed for better performance
- **Smooth Scrolling**: Enhanced navigation experience
- **Cross-Browser Compatible**: Works on all modern browsers
- **SEO Friendly**: Proper HTML structure and meta tags

## File Structure

```
Savni Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
└── [Image files]       # Your photography portfolio images
    ├── IMG-20250605-WA0016.jpg
    ├── IMG-20250605-WA0017.jpg
    ├── ...
    └── IMG-20250605-WA0030.jpg
```

## Setup Instructions

1. **Open the Website**: Simply open `index.html` in any modern web browser
2. **Local Server** (recommended): Use a local server for better performance:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using VS Code Live Server extension
   Right-click index.html → "Open with Live Server"
   ```

## Customization Guide

### 🖼️ Adding Your Photos
1. Replace the existing image files with your photography
2. Keep the same naming convention or update the HTML accordingly
3. Ensure images are optimized for web (recommended: 1200px max width)

### 🎨 Updating Content
- **Personal Information**: Edit the about section in `index.html`
- **Contact Details**: Update email and contact information
- **Social Media**: Add your social media links in the footer
- **Professional Photo**: Replace the placeholder in the about section

### 🎭 Styling Changes
- **Colors**: Modify the CSS custom properties in `styles.css`
- **Fonts**: Change the Google Fonts import and font-family declarations
- **Layout**: Adjust grid layouts and spacing in the CSS
- **Animations**: Customize animation timings and effects

### 📊 Adding Categories
1. Update the filter buttons in the HTML
2. Add corresponding `data-category` attributes to images
3. Update the JavaScript filter functionality if needed

## Technical Details

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

### Dependencies
- **Google Fonts**: Playfair Display & Inter
- **Font Awesome**: Icons for UI elements
- **EmailJS**: Contact form email functionality
- **No Framework Required**: Pure HTML, CSS, and JavaScript

### Performance Features
- **Lazy Loading**: Images load only when needed
- **Optimized CSS**: Minimal and efficient styling
- **Debounced Events**: Optimized scroll and resize handlers
- **Smooth Animations**: Hardware-accelerated CSS transitions

## SEO & Analytics

### SEO Features
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for all images
- Meta viewport for mobile
- Clean URL structure

### Adding Analytics
To add Google Analytics or other tracking:
1. Add the tracking script to the `<head>` section of `index.html`
2. Configure your tracking ID
3. Test the implementation

## Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings

### Netlify
1. Drag and drop the folder to Netlify
2. Your site will be live instantly
3. Custom domain can be configured

### Traditional Web Hosting
1. Upload all files to your web hosting provider
2. Ensure the main file is named `index.html`
3. Configure any necessary permissions

## Maintenance

### Regular Updates
- **Content**: Update portfolio images regularly
- **Contact Info**: Keep contact details current
- **Dependencies**: Update Font Awesome and Google Fonts links annually
- **Browser Testing**: Test on new browser versions

### Performance Monitoring
- **Image Optimization**: Compress new images before adding
- **Loading Speed**: Monitor with tools like PageSpeed Insights
- **Mobile Testing**: Regular testing on various devices

## Support & Credits

**Created for**: Savni Goyal (goyalsavni@gmail.com)
**Technologies Used**: HTML5, CSS3, JavaScript ES6+, Google Fonts, Font Awesome
**Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
**Cross-Platform**: Compatible with all modern devices and browsers

---
