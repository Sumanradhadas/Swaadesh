# Swaaddesh Restaurant Website - WebGlow Enhanced

## Project Overview
A modern Bihar-themed restaurant website featuring authentic design with enhanced performance and WebGlow branding. The site maintains its traditional warm color palette while incorporating modern web features.

## Recent Changes (November 2025)

### ✨ WebGlow Branding Integration
- Added "✨ Powered by WebGlow" credit in header (visible on desktop, hidden on mobile)
- Updated footer with WebGlow branding: "Designed & Developed by WebGlow"
- Golden glow effects on WebGlow branding matching the site's color scheme

### 🎨 Design Enhancements
- **Color Scheme**: Maintained original warm brown/golden theme (#2e2000, #FFD700, #FFA500)
- **Typography**: Fixed Samarkan font loading with corrected path (../assets/fonts/)
- **Animations**: Added smooth scroll animations using AOS library
- **Hover Effects**: Enhanced button and link transitions
- **Responsive Design**: Fully optimized for mobile and desktop

### ⚡ Performance Optimizations
- Fixed font loading path for faster render
- Added meta tags for SEO and social media sharing
- Optimized CSS structure
- Added theme-color meta tag (#0a0e27)

### 🔧 Technical Improvements
- Static Python server configured on port 5000
- Deployment configured for Replit autoscale
- Fixed HTML structure (removed duplicate closing tags)
- Added AOS scroll animation library
- Improved accessibility with proper meta tags

## Project Structure
```
├── assets/              # Images, fonts, and media files
│   ├── fonts/          # Samarkan custom font
│   ├── dine in/        # Menu images
│   └── drinks in/      # Drink menu images
├── styles/             # CSS files
│   ├── style.css       # Main stylesheet with WebGlow enhancements
│   ├── responsive.css  # Mobile responsiveness
│   └── social media.css
├── scripts/            # JavaScript files
│   ├── main.js        # Main functionality
│   └── animations.js  # Animation handlers
├── *.html             # HTML pages (index, about, menu, reviews, contact, etc.)
├── server.py          # Python static file server
└── replit.md          # This file

```

## Color Palette
- **Primary Brown**: #2e2000 (Navbar)
- **Accent Brown**: #361600 (Scrolled navbar)
- **Golden Yellow**: #FFD700 (Logo glow, WebGlow branding)
- **Orange**: #FFA500 (Secondary glow)
- **Footer**: #2C1A10
- **Text**: White on dark backgrounds

## Features
1. **Multi-page Navigation**: Home, About, Menu, Reviews, Contact, Social Media
2. **Image Slider**: Hero section with rotating restaurant images
3. **Menu System**: Dine-in and Drinks menus with modal viewing
4. **Awards Section**: Highlighting restaurant achievements
5. **Features Showcase**: Live screening, music, food, family dining
6. **Partner Integration**: Zomato, Swiggy, EazyDiner links
7. **Social Media**: Floating social icons
8. **Responsive Design**: Mobile-first approach

## WebGlow Branding
- **Header**: Subtle badge with sparkle animation (desktop only)
- **Footer**: "Web" (golden) + "Glow" (orange) with hover glow effects
- **Link**: https://webglowx.onrender.com/ (opens in new tab)

## Development

### Running Locally
```bash
python3 server.py
```
Server runs on: http://0.0.0.0:5000

### Deployment
Configured for Replit autoscale deployment:
- **Target**: autoscale (stateless)
- **Command**: `python3 server.py`
- **Port**: 5000

## Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Dependencies
- **AOS**: Scroll animation library (v2.3.1)
- **FontAwesome**: Icons (v6.4.2)
- **Python 3.11**: Static file server

## User Preferences
- ✅ Keep original warm brown/golden color scheme
- ✅ Add WebGlow branding (header + footer)
- ✅ Maintain restaurant theme authenticity
- ✅ Optimize performance and loading speed
- ✅ Ensure mobile responsiveness

## Notes
- Font path corrected to relative path for proper loading
- All pages include consistent header/footer with WebGlow branding
- Scroll animations enhance user experience without being intrusive
- Original design aesthetic preserved while modernizing codebase
