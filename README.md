# WeEdit - Professional Video Editing Services Landing Page

A modern, interactive landing page for WeEdit, a subscription-based video editing service designed for content creators, influencers, podcasters, and businesses.

## 🎥 About WeEdit

WeEdit is a professional video editing service that connects content creators with expert video editors. The platform offers subscription-based editing services for:

- **YouTubers** - Professional YouTube video editing and optimization
- **Influencers** - Brand collaboration videos and lifestyle content
- **Podcasters** - Transform audio podcasts into engaging video content
- **Businesses** - Corporate presentations, product demos, and marketing videos
- **Content Creators** - Social media content for TikTok, Instagram Reels, YouTube Shorts

## 🚀 Features

### Interactive Elements
- **3D Particle Animation Background** - Dynamic Three.js-powered particle system with sphere-to-cloud explosion effect
- **Custom Cursor** - Responsive cursor with hover effects
- **Before/After Image Slider** - Interactive slider showcasing video editing transformations
- **Testimonial Carousel** - Auto-rotating customer testimonials with manual navigation
- **Cost Calculator Slider** - Interactive pricing calculator based on user count
- **Video Integration** - Embedded YouTube video with custom overlay effects
- **Scroll Animations** - Smooth fade-in animations triggered by scroll position

### Responsive Design
- **Mobile-First Approach** - Fully responsive design optimized for all devices
- **Dark Theme** - Modern dark color scheme with purple accent colors
- **Glass Morphism Effects** - Semi-transparent elements with backdrop blur
- **Smooth Transitions** - CSS and JavaScript-powered smooth animations

### SEO Optimization
- **Comprehensive Meta Tags** - Full SEO meta tag implementation
- **Open Graph Tags** - Social media sharing optimization
- **Twitter Cards** - Twitter-specific metadata
- **LinkedIn Meta Tags** - Professional network optimization
- **Schema.org Structured Data** - Rich snippets for search engines
- **Hidden SEO Content** - Additional keyword-rich content for search rankings

### Performance Features
- **Loading Screen** - Animated percentage-based loading experience
- **Session Storage** - Optimized loading for return visitors
- **CDN Resources** - Fast loading external dependencies
- **Optimized Images** - Placeholder images with error handling
- **Lazy Loading Effects** - Performance-optimized scroll animations

## 🛠 Technologies Used

### Core Technologies
- **HTML5** - Semantic markup with modern HTML5 features
- **CSS3** - Advanced styling with custom properties and animations
- **JavaScript ES6+** - Modern JavaScript for interactive functionality

### CSS Framework
- **Tailwind CSS** (CDN) - Utility-first CSS framework for rapid UI development
  - Version: Latest (via CDN)
  - Purpose: Responsive design, utility classes, and consistent styling

### 3D Graphics
- **Three.js** (r128) - 3D graphics library for WebGL rendering
  - Version: r128
  - CDN: `https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js`
  - Features: Particle systems, camera controls, 3D animations

### Typography
- **Google Fonts - Inter** - Modern, clean typography
  - Weights: 300, 400, 500, 600, 700, 800
  - Optimized loading with `display=swap`

### External Integrations
- **YouTube Embed API** - Video integration with custom controls
- **Google Analytics 4** - Web analytics (placeholder implementation)
- **Facebook Pixel** - Social media tracking (placeholder implementation)
- **LinkedIn Insight Tag** - Professional network analytics (placeholder implementation)

### Development Tools
- **IntersectionObserver API** - Scroll-triggered animations
- **Web APIs**: 
  - Canvas API (for Three.js rendering)
  - RequestAnimationFrame (for smooth animations)
  - SessionStorage (for loading optimization)

## 📁 Project Structure

```
landingPage/
├── v4.html              # Main landing page file
├── README.md             # Project documentation
└── .git/                # Git repository
```

## 🎨 Design Features

### Color Scheme
- **Primary Background**: `#1a202c` (Dark gray)
- **Secondary Background**: `#2d3748` (Medium gray)
- **Accent Colors**: Purple gradient (`#9370db`, `#8a2be2`, `#4b0082`)
- **Text Colors**: White and light gray variants

### Animations
- **Page Load**: Percentage-based loading screen
- **3D Particles**: Sphere explosion into floating cloud
- **Scroll Reveals**: Fade-in animations on scroll
- **Hover Effects**: Card lifting and button transformations
- **Cursor**: Custom cursor with hover states

### Interactive Components
1. **Header Navigation** - Fixed header with call-to-action buttons
2. **Hero Section** - Full-screen introduction with 3D background
3. **Process Video** - Embedded YouTube video with custom overlay
4. **How It Works** - 4-step process explanation
5. **Before/After Slider** - Interactive image comparison
6. **Pricing Plans** - Subscription tiers with features
7. **Cost Calculator** - Interactive pricing slider
8. **Testimonials** - Rotating customer feedback
9. **Footer** - Contact information and links

## 🔧 Setup Instructions

### Local Development
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd landingPage
   ```

2. **Open the file**:
   - Simply open `v4.html` in a modern web browser
   - Or serve using a local server for best performance:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

3. **View the website**:
   - Open `http://localhost:8000/v4.html` in your browser

### Production Deployment
1. **Update tracking IDs**:
   - Replace `GA_TRACKING_ID` with your Google Analytics ID
   - Replace `FACEBOOK_PIXEL_ID` with your Facebook Pixel ID
   - Replace `LINKEDIN_PARTNER_ID` with your LinkedIn Partner ID

2. **Update content**:
   - Replace placeholder images with actual before/after examples
   - Update contact information and social media links
   - Customize testimonials with real customer feedback

3. **Deploy**:
   - Upload to your web hosting service
   - Ensure HTTPS is enabled for optimal performance

## 🌐 Browser Support

- **Chrome** 88+ ✅
- **Firefox** 85+ ✅
- **Safari** 14+ ✅
- **Edge** 88+ ✅
- **Mobile browsers** ✅

### Required Features
- WebGL support (for Three.js)
- CSS Grid and Flexbox
- IntersectionObserver API
- ES6+ JavaScript features

## 📊 SEO Features

### Meta Tags Implementation
- Primary SEO meta tags
- Open Graph for social sharing
- Twitter Card metadata
- LinkedIn-specific tags
- Canonical URL specification

### Structured Data
- Organization schema
- Service offerings
- Contact information
- Pricing information

### Content Optimization
- Semantic HTML structure
- Alt text for images
- Descriptive meta descriptions
- Keyword-optimized content
- Hidden SEO content section

## 🎯 Target Audience

### Primary Users
- Content creators and YouTubers
- Social media influencers
- Podcast creators
- Small business owners
- Digital marketing agencies

### Use Cases
- YouTube video editing
- Podcast video creation
- Social media content
- Marketing videos
- Corporate presentations
- Educational content

## 🔮 Future Enhancements

### Planned Features
- User authentication system
- File upload interface
- Project management dashboard
- Real-time collaboration tools
- Advanced pricing calculator
- Multi-language support

### Technical Improvements
- Service worker for offline functionality
- Progressive Web App features
- Advanced analytics implementation
- A/B testing framework
- Performance monitoring

## 📝 License

This project is proprietary to WeEdit. All rights reserved.

## 📞 Contact

- **Website**: [https://www.weedit.co.in](https://www.weedit.co.in)
- **Email**: support@weedit.co.in
- **Social Media**: Follow @WeEditOfficial

---

*Built with ❤️ for content creators worldwide*
