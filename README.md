# EduTransform - AI-Powered Educational Platform

A modern, responsive website for EduTransform - an AI-powered platform that converts static learning materials into interactive, story-based educational content.

## 🌟 Features

### Landing Page
- **Hero Section** - Engaging introduction with animated elements and statistics
- **Problem Section** - Highlights issues with traditional static learning materials
- **Features Section** - Showcase of AI transformation capabilities
- **Benefits Section** - Proven results with visual data representations
- **Pricing Plans** - Three tiers: Individual, School, and Enterprise
- **Testimonials** - Social proof from educators and institutions
- **FAQ Section** - Accordion-style frequently asked questions
- **Contact Form** - Functional form with validation
- **Newsletter Signup** - Email subscription functionality

### About Page
- Mission statement and company values
- Research partnerships and scientific backing
- Company timeline and journey
- Team member profiles
- Investors and awards

### How It Works Page
- Step-by-step process visualization
- Before/after content transformations
- Interactive demo section
- Detailed feature explanations

### Resources Page
- Research articles on interactive learning
- Case studies from real implementations
- Best practices guides
- Tutorial and video library

## 🎨 Design Features

- **Modern, Clean Interface** - Professional design suitable for the education sector
- **Responsive Design** - Fully functional on desktop, tablet, and mobile devices
- **Smooth Animations** - Fade-in effects, hover states, and scroll-triggered animations
- **Gradient Color Scheme** - Purple to cyan gradients for a modern look
- **Accessible** - Semantic HTML and ARIA labels for screen readers
- **Fast Loading** - Optimized CSS and vanilla JavaScript for performance

## 📁 Project Structure

```
edutransform/
├── index.html              # Main landing page
├── pages/
│   ├── about.html          # About page
│   ├── how-it-works.html   # How it works page
│   └── resources.html      # Resources/blog page
├── css/
│   └── styles.css          # Main stylesheet with all design
└── js/
    └── main.js             # JavaScript for interactivity
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for testing)

### Installation

1. **Clone or download the project**
   ```bash
   cd edutransform
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser, OR
   - Use a local server for better development experience:
     ```bash
     # Using Python 3
     python -m http.server 8000

     # Using Node.js (with http-server)
     npx http-server
     ```

3. **Navigate to the website**
   - Open your browser and go to `http://localhost:8000`

## 🎯 Key Functionality

### Navigation
- Responsive navbar with mobile hamburger menu
- Smooth scrolling to sections
- Active link highlighting

### Interactive Elements
- **FAQ Accordion** - Click questions to reveal answers
- **Pricing Toggle** - Switch between monthly/yearly pricing
- **Comparison Tabs** - View before/after transformations
- **Contact Forms** - Validated forms with success notifications
- **Back to Top Button** - Appears after scrolling down

### Animations
- Scroll-triggered fade-in animations
- Hover effects on cards and buttons
- Animated statistics counters
- Floating background shapes

### Forms
- Email validation
- Required field validation
- Success/error notifications
- Form reset after submission

## 🎨 Customization

### Colors
Edit CSS variables in `css/styles.css`:
```css
:root {
    --primary: #4F46E5;
    --secondary: #06B6D4;
    --accent: #F59E0B;
    /* ... more variables */
}
```

### Content
- Edit text content directly in HTML files
- Update statistics and numbers
- Change testimonials and case studies
- Modify pricing plans

### Images
- Replace placeholder images with your own
- Update team member photos
- Add custom graphics

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## 🔧 JavaScript Modules

The main JavaScript file (`js/main.js`) includes:
- Navigation handling
- Scroll animations using Intersection Observer
- Pricing toggle functionality
- FAQ accordion
- Form validation and submission
- Back to top button
- Smooth scrolling
- Count-up animations for statistics
- Notification system

## 🌐 External Dependencies

- **Font Awesome 6.4.0** - Icons (CDN)
- **Google Fonts** - Typography (system fonts fallback)

## 📄 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📞 Support

For questions or support, please use the contact form on the website.

---

Built with ❤️ for educators worldwide
