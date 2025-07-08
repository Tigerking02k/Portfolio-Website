# 🚀 Nayan's Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This portfolio showcases your skills, projects, and provides a professional way to connect with potential employers or clients.

![Portfolio Preview](https://via.placeholder.com/800x400/667eea/ffffff?text=Portfolio+Website+Preview)

## ✨ Features

### 🎨 **Design & User Experience**
- **Modern Design**: Clean, professional layout with gradient backgrounds and smooth animations
- **Responsive Design**: Fully responsive across all devices (desktop, tablet, mobile)
- **Dark Mode Toggle**: Switch between light and dark themes
- **Smooth Scrolling**: Seamless navigation between sections
- **Loading Animation**: Professional loading screen with spinner

### 🎯 **Interactive Elements**
- **Typing Effect**: Dynamic text animation in the hero section
- **Scroll Animations**: Elements fade in as you scroll
- **Hover Effects**: Interactive hover animations on cards and buttons
- **Particle Background**: Animated particles in the hero section
- **Contact Form**: Functional contact form with validation
- **Project Filters**: Filter projects by category (Web, Mobile, AI/ML, Data Science)

### 📱 **Sections**
1. **Hero Section**: Introduction with animated typing effect
2. **About Section**: Personal information, education, interests, and skills
3. **Projects Section**: Showcase of your work with filtering capabilities
4. **Contact Section**: Contact form and information
5. **Footer**: Social media links and copyright

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)**: Interactive functionality and dynamic content
- **Font Awesome**: Icons for enhanced visual appeal
- **Google Fonts**: Typography (Poppins)

## 📦 Installation

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   cd portfolio-website
   ```

2. **Open the website**
   - Double-click `index.html` to open in your browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     ```

3. **View the website**
   - Navigate to `http://localhost:8000` in your browser

## 🎨 Customization

### Personal Information

#### 1. Hero Section
Edit the following in `index.html`:
```html
<h1>Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="typing-text">Your Title</h2>
<p>Your description here...</p>
```

#### 2. About Section
```html
<div class="about-text">
    <h3>Who I Am</h3>
    <p>Your personal description...</p>
    
    <div class="education-info">
        <h4><i class="fas fa-graduation-cap"></i> Education</h4>
        <div class="education-item">
            <h5>Your Degree</h5>
            <p><i class="fas fa-calendar"></i> 2021 - Present</p>
            <p><i class="fas fa-university"></i> Your University</p>
        </div>
    </div>
    
    <div class="skills">
        <h4><i class="fas fa-code"></i> Technical Skills</h4>
        <div class="skill-tags">
            <span class="skill-tag">Your Skill 1</span>
            <span class="skill-tag">Your Skill 2</span>
            <!-- Add more skills -->
        </div>
    </div>
</div>
```

#### 3. Projects Section
```html
<div class="project-card" data-category="web">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
        <div class="project-overlay">
            <div class="project-tech-stack">
                <span>React</span>
                <span>Node.js</span>
                <span>MongoDB</span>
            </div>
        </div>
    </div>
    <div class="project-content">
        <div class="project-header">
            <h3>Your Project Title</h3>
            <span class="project-category">Web Development</span>
        </div>
        <p>Project description...</p>
        <div class="project-features">
            <span class="feature-tag">Feature 1</span>
            <span class="feature-tag">Feature 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="btn btn-primary">
                <i class="fab fa-github"></i> View Code
            </a>
            <a href="your-live-link" class="btn btn-secondary">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

#### 4. Contact Information
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h4>Email</h4>
        <p>your.email@example.com</p>
        <small>Best way to reach me</small>
    </div>
</div>
```

### Styling Customization

#### Colors
Edit the CSS variables in `styles.css`:
```css
/* Primary gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Primary accent color */
color: #667eea;

/* Secondary colors */
.interest-tag {
    background: linear-gradient(45deg, #ff6b6b, #ee5a24);
}
```

#### Fonts
Change the font family in `styles.css`:
```css
body {
    font-family: 'Your Preferred Font', sans-serif;
}
```

#### Animations
Modify animation speeds and effects:
```css
/* Animation duration */
transition: all 0.3s ease;

/* Animation keyframes */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

### JavaScript Features

#### Typing Effect
Customize the typing text in `script.js`:
```javascript
const texts = [
    'Your Title 1',
    'Your Title 2',
    'Your Title 3',
    'Your Title 4'
];
```

#### Project Filters
The website includes filter buttons for:
- All Projects
- Web Development
- Mobile Apps
- AI/ML
- Data Science

#### Contact Form
The contact form includes:
- Name validation
- Email validation
- Message validation
- Success/error notifications
- Privacy policy checkbox

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

### Mobile Features
- Collapsible navigation
- Touch-friendly buttons
- Optimized layouts for small screens
- Responsive images and grids

## 🌐 Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to **Settings** > **Pages**
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed automatically
3. Get a custom domain or use the provided Netlify URL

### Vercel
1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Vercel will automatically deploy your site
3. Get a custom domain or use the provided Vercel URL

### Other Hosting Services
- **Firebase Hosting**: Google's hosting service
- **AWS S3**: Amazon's static website hosting
- **DigitalOcean App Platform**: Simple deployment
- **Heroku**: For more complex applications

## 🔧 Advanced Features

### Adding New Sections
1. Create a new section in `index.html`:
```html
<section id="new-section" class="section">
    <div class="container">
        <h2 class="section-title">Section Title</h2>
        <!-- Your content -->
    </div>
</section>
```

2. Add navigation link:
```html
<li><a href="#new-section">Section Name</a></li>
```

### Adding Animations
1. Add CSS animation:
```css
.your-element {
    opacity: 0;
    transform: translateY(30px);
    transition: all 0.6s ease;
}

.your-element.visible {
    opacity: 1;
    transform: translateY(0);
}
```

2. Add JavaScript observer:
```javascript
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('visible');
        }
    });
});

observer.observe(document.querySelector('.your-element'));
```

### Performance Optimization
- Optimize images for web
- Minify CSS and JavaScript for production
- Use CDN for external libraries
- Enable gzip compression on your server

## 📄 File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript functionality
├── README.md           # This file
├── .gitignore          # Git ignore file
└── assets/             # Optional: for images and other assets
    ├── images/
    └── icons/
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

If you need help customizing your portfolio:
1. Check the comments in the code files
2. Refer to this README for common customizations
3. Open an issue on GitHub for bugs or feature requests
4. Modify the code according to your needs

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- Modern CSS techniques and animations
- JavaScript ES6+ features
- The open-source community for inspiration

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/portfolio-website)
![GitHub forks](https://img.shields.io/github/forks/yourusername/portfolio-website)
![GitHub issues](https://img.shields.io/github/issues/yourusername/portfolio-website)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/portfolio-website)

---

**⭐ If you find this project helpful, please give it a star on GitHub!**

**Happy coding! 🚀** 