# Bridgeview Maintenance - Standalone HTML Website

This folder contains a standalone HTML version of the Bridgeview Maintenance website, extracted from the Laravel project.

## Files Structure

```
htmlFolder/
├── index.html          # Main HTML file
├── css/               # CSS stylesheets
│   ├── app.css
│   └── bootstrap.min.css
├── js/                # JavaScript files
│   └── main.js
├── lib/               # Third-party libraries
│   ├── animate/
│   ├── counterup/
│   ├── easing/
│   ├── owlcarousel/
│   └── wow/
├── img/               # Images and assets
│   └── new/           # New images
└── README.md          # This file
```

## Features

✅ **Fully Responsive Design**
✅ **Smooth Animations** - WOW.js reveal animations on scroll
✅ **Interactive Elements** - Hover effects, smooth scrolling
✅ **Modern UI/UX** - Bootstrap 5 with custom styling
✅ **Contact Form** - Ready for backend integration
✅ **SEO Optimized** - Proper meta tags and structure

## Animations Applied

- **Hero Section**: Background with overlay
- **Stats Section**: Staggered fadeInUp animations (0.4s, 0.5s, 0.6s delays)
- **About Section**: fadeInLeft (images) and fadeInRight (text)
- **Features Section**: Staggered fadeInUp animations (0.3s, 0.4s, 0.5s delays)
- **Services Section**: Staggered fadeInUp animations (0.2s to 0.6s delays)
- **Projects Section**: Staggered fadeInUp animations (0.3s to 0.6s delays)
- **Contact Section**: fadeInLeft (info) and fadeInRight (form)

## How to Use

1. Open `index.html` in any modern web browser
2. All animations will work automatically on scroll
3. No server required - works as static HTML

## JavaScript Libraries Included

- **jQuery 3.6.4** - DOM manipulation
- **Bootstrap 5.0.0** - UI framework
- **WOW.js** - Scroll reveal animations
- **Easing.js** - Smooth animation transitions
- **Waypoints.js** - Scroll trigger points
- **CounterUp.js** - Animated counters

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Customization

To modify animations, edit the `data-wow-*` attributes in the HTML:
- `data-wow-duration` - Animation duration
- `data-wow-delay` - Animation delay
- `class="wow fadeInUp"` - Animation type

## Contact

For questions about this website, contact: info@bridgeviewmaintenance.com
