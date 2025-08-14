# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This project showcases a clean, professional design with smooth animations and interactive elements.

## 🚀 Features

### Design & Layout
- **Modern Design**: Clean, minimalist design with beautiful gradients
- **Responsive Layout**: Mobile-first approach, works perfectly on all devices
- **Professional Typography**: Uses Inter font family for excellent readability
- **Smooth Animations**: Scroll-triggered animations and hover effects

### Sections
- **Hero Section**: Eye-catching introduction with gradient text effects
- **About Section**: Personal information and background
- **Skills Section**: Technical skills organized by category (Frontend, Backend, Tools)
- **Projects Section**: Featured projects with descriptions and links
- **Contact Section**: Contact form and social media links
- **Navigation**: Smooth scrolling navigation with mobile hamburger menu

### Interactive Elements
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Seamless navigation between sections
- **Form Validation**: Contact form with email validation
- **Notification System**: Success/error notifications for form submissions
- **Loading Animation**: Beautiful loading screen on page load
- **Parallax Effects**: Subtle parallax scrolling for enhanced UX

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Font Awesome**: Icons for skills and social links
- **Google Fonts**: Inter font family

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── css/
│   └── master.css      # All styles and animations
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Image assets (if any)
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required

### Installation

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **That's it!** The portfolio is ready to use

### Alternative Setup Methods

#### Method 1: Direct File Opening
```bash
# Navigate to the project directory
cd Portfolio

# Open in default browser
start index.html  # Windows
open index.html   # macOS
xdg-open index.html  # Linux
```

#### Method 2: Live Server (VS Code)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

#### Method 3: Python Simple Server
```bash
# Navigate to project directory
cd Portfolio

# Start Python server
python -m http.server 8000

# Open browser and go to
# http://localhost:8000
```

## 🎨 Customization Guide

### Personal Information
Update the following sections in `index.html`:

#### Hero Section
```html
<h1 class="title">Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">Your Title</h2>
<p class="hero-description">Your description here</p>
```

#### About Section
```html
<p>Your personal description and background</p>
```

#### Contact Information
```html
<span>your.email@example.com</span>
<span>+1 (555) 123-4567</span>
<span>Your City, Country</span>
```

### Projects
Replace the sample projects in the Projects section:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">Code</a>
        </div>
    </div>
</div>
```

### Skills
Update the skills in the Skills section:

```html
<div class="skill-item">
    <i class="fab fa-html5"></i>
    <span>HTML5</span>
</div>
```

### Social Links
Update the social media links in the Contact section:

```html
<a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
<a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
```

### Colors and Styling
Modify the color scheme in `css/master.css`:

```css
/* Primary gradient colors */
.btn-primary {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

/* Highlight color */
.highlight {
    color: #6c63ff;
}
```

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

### Mobile Features
- Hamburger navigation menu
- Touch-friendly buttons and links
- Optimized typography for small screens
- Responsive grid layouts

## 🎯 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🔧 JavaScript Features

### Core Functionality
- **Mobile Navigation Toggle**: Hamburger menu functionality
- **Smooth Scrolling**: Navigation between sections
- **Scroll Animations**: Elements animate when scrolled into view
- **Form Handling**: Contact form validation and submission
- **Notification System**: User feedback for form actions
- **Loading Screen**: Initial page load animation

### Animation Effects
- **Typing Effect**: Hero title typing animation
- **Fade-in Animations**: Elements appear on scroll
- **Hover Effects**: Interactive element animations
- **Parallax Scrolling**: Hero section parallax effect

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
