# Sanket Singh Sameer - Portfolio Website

A beautiful, modern, and fully responsive portfolio website built with HTML5, CSS3, and JavaScript. Showcasing the work and skills of Sanket Singh Sameer, a B.Tech student in Mathematics & Computing at NIT Hamirpur. Features smooth animations, interactive elements, and a clean design that looks great on all devices.

## ✨ Features

- **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Hover effects, scroll animations, and dynamic content
- **Performance Optimized** - Fast loading times and optimized images
- **Cross-browser Compatible** - Works on all modern browsers
- **SEO Friendly** - Proper meta tags and semantic HTML
- **Accessible** - WCAG 2.1 compliant with keyboard navigation support
- **Dark Mode Toggle** - Switch between light and dark themes
- **Contact Form** - Functional contact form with validation
- **Smooth Scrolling** - Smooth navigation between sections
- **Back to Top Button** - Easy navigation for better UX
- **Preloader** - Professional loading animation
- **Social Media Integration** - Links to social profiles

## 🚀 Live Demo

Open `index.html` in your browser to see the portfolio in action.

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
│
└── assets/
    ├── resume.txt      # Sample resume file
    └── inspo.jpg       # Inspiration image
```

## 🛠️ Technologies Used

### Core Technologies
- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality

### External Libraries (CDN)
- **AOS (Animate On Scroll)** - Scroll animations
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Poppins font)

### Features Implemented
- Responsive Grid Layout
- CSS Animations and Transitions
- JavaScript DOM Manipulation
- Intersection Observer API
- Local Storage (for theme preference)
- Form Validation
- Smooth Scrolling
- Mobile Navigation

## 📱 Responsive Breakpoints

- **Desktop:** 1200px and above
- **Laptop:** 992px - 1199px
- **Tablet:** 768px - 991px
- **Mobile:** Below 768px
- **Small Mobile:** Below 480px

## 🎨 Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

```html
<!-- Update navigation logo -->
<div class="nav-logo">
    <span>Your Name.</span>
</div>

<!-- Update hero section -->
<h1 class="hero-title">
    Hi, I'm <span class="text-gradient">Your Name</span>
</h1>
<h2 class="hero-subtitle">Your Job Title</h2>
```

### 2. Colors and Theme

Update colors in `styles.css`:

```css
/* Primary gradient colors */
background: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);

/* Update CSS variables for consistent theming */
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --text-color: #333;
    --bg-color: #ffffff;
}
```

### 3. Content Sections

#### About Section
```html
<!-- Update about content -->
<div class="about-text">
    <h3>Your personal tagline</h3>
    <p>Your personal description...</p>
</div>
```

#### Skills Section
```html
<!-- Add/remove skill cards -->
<div class="skill-card">
    <div class="skill-icon">
        <i class="your-icon"></i>
    </div>
    <h3>Your Skill</h3>
    <p>Description of your expertise</p>
</div>
```

#### Projects Section
```html
<!-- Update project information -->
<div class="project-content">
    <h3>Your Project Name</h3>
    <p>Project description</p>
    <div class="project-tags">
        <span class="tag">Technology 1</span>
        <span class="tag">Technology 2</span>
    </div>
</div>
```

### 4. Images

Replace the placeholder images with your own:
- Hero image: Update the `src` in the hero section
- About image: Replace in the about section
- Project images: Update project card images
- Add your profile photo

### 5. Social Links

Update social media links in the contact section:

```html
<div class="social-links">
    <a href="your-linkedin-url" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="your-github-url" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <!-- Add more social links -->
</div>
```

### 6. Contact Information

Update your contact details:

```html
<div class="contact-details">
    <h4>Email</h4>
    <span>your-email@example.com</span>
</div>
```

## 🚀 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source as "Deploy from a branch"
4. Select "main" branch and "/" (root) folder
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Create account on Netlify
2. Connect your GitHub repository
3. Deploy with default settings
4. Your site will be live with a custom URL

### Vercel
1. Create account on Vercel
2. Import your GitHub repository
3. Deploy with default settings
4. Get your custom domain

### Traditional Web Hosting
1. Upload all files to your web hosting provider
2. Ensure `index.html` is in the root directory
3. Your site will be accessible via your domain

## 📧 Contact Form Setup

The contact form currently shows a success message for demonstration. To make it functional:

### Option 1: Formspree
1. Sign up at [Formspree](https://formspree.io/)
2. Update the form action:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: Netlify Forms
1. Add `netlify` attribute to your form:
```html
<form class="contact-form" netlify>
```

### Option 3: EmailJS
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Follow their integration guide
3. Update the JavaScript form handler

## 🔧 Performance Optimization

### Images
- Use WebP format for better compression
- Implement lazy loading for images
- Optimize image sizes for different screen resolutions

### CSS
- Minify CSS for production
- Remove unused CSS rules
- Use CSS containment for better performance

### JavaScript
- Minify JavaScript for production
- Use code splitting for large applications
- Implement service workers for offline functionality

## 📊 SEO Optimization

### Meta Tags
```html
<meta name="description" content="Your portfolio description">
<meta name="keywords" content="your, relevant, keywords">
<meta property="og:title" content="Your Name - Portfolio">
<meta property="og:description" content="Your description">
<meta property="og:image" content="path/to/your/image.jpg">
```

### Structured Data
Add JSON-LD structured data for better search engine understanding.

## 🐛 Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

If you need help customizing this portfolio or have any questions:

- Create an issue in the repository
- Check the existing documentation
- Review the code comments for guidance

## 🙏 Acknowledgments

- [AOS Library](https://michalsnik.github.io/aos/) for scroll animations
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- [Unsplash](https://unsplash.com/) for placeholder images

---

Made with ❤️ by Sanket Singh Sameer

**Happy Coding! 🚀**

## 👨‍💻 About Sanket Singh Sameer

- 🎓 B.Tech in Mathematics & Computing at NIT Hamirpur
- 🏆 JEE Mains 2024: 98.8 percentile
- 💻 Full Stack Developer specializing in MERN stack
- 🌟 Active member of Computer Science Engineering Society (CSEC)
- 📧 Contact: sanketsingshameer@proton.me
- 🔗 LinkedIn: [sanket-singh-sameer](https://linkedin.com/in/sanket-singh-sameer)
- 💾 GitHub: [sanket-singh-sameer](https://github.com/sanket-singh-sameer)
