# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a WeEdit landing page - a single-page website for a professional video editing service targeting content creators, influencers, and podcasters. The project is a static HTML site with advanced interactive features.

## Development Commands

### Local Development
```bash
# Serve locally using Python
python -m http.server 8000

# Or using Node.js
npx serve .

# Or using PHP
php -S localhost:8000

# Access at: http://localhost:8000/public/index.html or http://localhost:8000/src/index.html
```

### Deployment
```bash
# Deploy to Firebase Hosting
firebase deploy

# The firebase.json configures hosting to serve from the 'public' directory
# All routes redirect to /index.html for SPA-like behavior
```

## Architecture

### File Structure
- `public/index.html` - Production version of the landing page
- `src/index.html` - Development/source version (appears identical to public)
- `firebase.json` - Firebase hosting configuration
- `README.md` - Comprehensive project documentation

### Technology Stack
- **Frontend**: Vanilla HTML5, CSS3, JavaScript ES6+
- **Styling**: Tailwind CSS (via CDN)
- **3D Graphics**: Three.js r128 (via CDN)
- **Typography**: Google Fonts - Inter
- **Hosting**: Firebase Hosting
- **Analytics**: Google Analytics 4, Facebook Pixel, LinkedIn Insight Tag (placeholder IDs)

### Key Interactive Components

1. **3D Particle System**: Three.js-powered background with sphere-to-cloud explosion animation
2. **Custom Cursor**: Interactive cursor with hover effects
3. **Before/After Image Slider**: Comparison slider for showcasing video transformations
4. **Testimonial Carousel**: Auto-rotating customer testimonials
5. **Cost Calculator**: Interactive pricing slider based on user count
6. **Loading Screen**: Animated percentage-based loader with session storage optimization
7. **Scroll Animations**: IntersectionObserver-based reveal animations

### JavaScript Architecture
The page uses vanilla JavaScript with several key modules:
- **Three.js Scene Setup**: Particle system with dynamic animations
- **IntersectionObserver**: For scroll-triggered animations
- **Event Listeners**: Mouse tracking, slider interactions, carousel controls
- **Session Storage**: Loading optimization for return visitors

### External Dependencies (CDN)
- Tailwind CSS: Latest version
- Three.js: r128 from cdnjs.cloudflare.com
- Google Fonts: Inter (300-800 weights)

### SEO Implementation
- Comprehensive meta tags (primary, Open Graph, Twitter Cards, LinkedIn)
- Schema.org structured data
- Hidden SEO content section with keyword-rich text
- Semantic HTML structure

### Analytics Setup
To deploy to production, replace placeholder IDs:
- `GA_TRACKING_ID` → Your Google Analytics ID
- `FACEBOOK_PIXEL_ID` → Your Facebook Pixel ID  
- `LINKEDIN_PARTNER_ID` → Your LinkedIn Partner ID

### Browser Requirements
- WebGL support (for Three.js)
- CSS Grid and Flexbox
- IntersectionObserver API
- ES6+ JavaScript features

## Development Notes

- The site is purely static - no build process or package management
- Both `public/` and `src/` contain identical HTML files
- All styling uses Tailwind utility classes
- JavaScript is embedded directly in HTML files
- External resources are loaded via CDN for performance
- The site is mobile-responsive with a mobile-first approach

## Content Areas

The landing page includes these main sections:
- Header with navigation and CTA buttons
- Hero section with 3D particle background
- Process video (YouTube embed)
- How It Works (4-step process)
- Before/After showcase slider
- Pricing plans
- Interactive cost calculator
- Customer testimonials carousel
- Footer with contact information