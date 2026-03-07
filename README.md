# Developer Portfolio Website

A modern, minimalistic, and fully responsive portfolio website built with pure HTML, CSS, and JavaScript. Perfect for computer science students and developers looking to showcase their skills, projects, and achievements.

## 🌟 Features

- **Fully Responsive Design** - Optimized for mobile, tablet, and desktop devices
- **Dark/Light Mode Toggle** - User-friendly theme switching with persistent preferences
- **Smooth Scrolling Navigation** - Seamless navigation between sections
- **Mobile Hamburger Menu** - Clean and functional mobile navigation
- **Scroll Reveal Animations** - Engaging animations as you scroll
- **Project Showcase** - Display your projects with modern card layouts
- **Skills Section** - Organized categorization of technical skills
- **Certificates Gallery** - Showcase your achievements and certifications
- **Contact Form** - Simple and elegant contact form UI
- **Performance Optimized** - Fast loading with lazy loading images
- **Clean Code** - Well-commented and organized code structure

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet with responsive design
├── script.js           # JavaScript for interactivity
├── README.md           # Project documentation
│
└── assets/             # Assets folder
    ├── profile.jpg     # Profile image (add your own)
    ├── certificates/   # Certificate images folder
    │   ├── nptel-oop.jpg
    │   ├── nptel-java.jpg
    │   ├── ugc-python.jpg
    │   └── webathon.jpg
    │
    └── project-images/ # Project images folder
        ├── snake-game.jpg
        ├── voting-system.jpg
        ├── search-engine.jpg
        ├── learnable.jpg
        └── annadatahub.jpg
```

## 🚀 How to Run the Project

### Method 1: Using VS Code Live Server (Recommended)

1. **Install VS Code** (if not already installed)
   - Download from [https://code.visualstudio.com/](https://code.visualstudio.com/)

2. **Install Live Server Extension**
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X on Mac)
   - Search for "Live Server" by Ritwick Dey
   - Click "Install"

3. **Open the Project**
   - Open VS Code
   - Go to File > Open Folder
   - Select the `portfolio` folder

4. **Launch Live Server**
   - Right-click on `index.html` in the file explorer
   - Select "Open with Live Server"
   - Your default browser will automatically open the portfolio

   **OR**
   
   - Click the "Go Live" button in the bottom right corner of VS Code

5. **View Your Portfolio**
   - The website will open at `http://127.0.0.1:5500` (or similar)
   - Any changes you make will automatically refresh in the browser

### Method 2: Direct Browser Opening

1. Navigate to the `portfolio` folder on your computer
2. Double-click on `index.html`
3. The portfolio will open in your default web browser

**Note:** Some features may not work properly with this method due to browser security restrictions.

### Method 3: Using Python HTTP Server

If you have Python installed:

```bash
# Navigate to the portfolio folder
cd path/to/portfolio

# For Python 3.x
python -m http.server 8000

# For Python 2.x
python -m SimpleHTTPServer 8000
```

Then open your browser and go to `http://localhost:8000`

## 🎨 Customization Guide

### Adding Your Information

#### 1. Update Personal Information
Edit the following sections in `index.html`:
- Name, role, and introduction in the Hero section
- About Me text in the About section
- Contact information (email, phone, GitHub, LinkedIn)

#### 2. Add Your Profile Picture
- Save your profile picture as `profile.jpg` in the `assets/` folder
- Recommended size: 500x500px or larger (square aspect ratio)
- Supported formats: JPG, PNG

#### 3. Add Project Images
- Add your project screenshots to `assets/project-images/`
- Update the image src in the project cards
- Recommended size: 1200x600px or similar aspect ratio

#### 4. Add Certificate Images
- Add your certificate images to `assets/certificates/`
- Update the image src in the certificate cards
- Recommended size: 1200x900px or A4 aspect ratio

#### 5. Update Project Links
- Replace `href="#"` in project cards with actual project URLs
- Update GitHub and LinkedIn URLs with your profile links

#### 6. Customize Colors
Edit CSS variables in `style.css`:
```css
:root {
    --accent-primary: #3182ce;  /* Change primary color */
    --accent-secondary: #2c5282; /* Change secondary color */
}
```

#### 7. Add Resume Download Link
- Save your resume as `resume.pdf` in the `assets/` folder
- Update the resume download button href:
```html
<a href="assets/resume.pdf" class="btn btn-secondary" download>
```

## 📝 Sections Overview

### 1. **Hero Section**
- Profile image with hover effect
- Name and role
- Brief introduction
- Email and resume download buttons
- Social media links

### 2. **About Section**
- Personal introduction
- Educational background
- Career interests

### 3. **Skills Section**
- Organized by categories:
  - Programming Languages
  - Frameworks & Libraries
  - Databases
  - Tools
  - Platforms & IDEs

### 4. **Projects Section**
- Project cards with images
- Project descriptions
- Technology tags
- Links to live projects or repositories

### 5. **Hackathon Experience**
- Hackathon participation details
- Team collaboration experience

### 6. **Certificates Section**
- Certificate cards with images
- Course/certification names
- Issuing organizations

### 7. **Contact Section**
- Contact information display
- Contact form (UI only, no backend)

## 🔧 Technical Details

### Technologies Used
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables, Grid, and Flexbox
- **JavaScript (ES6+)** - Vanilla JS for all interactions

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

### Performance Features
- Lazy loading images
- Optimized animations
- Debounced scroll events
- Minimal external dependencies

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 768px - 481px
- **Mobile**: < 480px

## 🎯 Key Features Explained

### Dark/Light Mode Toggle
- Saves preference to localStorage
- Smooth transition between themes
- Custom color variables for easy theme management

### Smooth Scrolling
- Native smooth scroll behavior
- Offset for fixed navbar
- Active section highlighting in navigation

### Mobile Menu
- Hamburger animation
- Slide-in menu
- Auto-close on link click or outside click

### Scroll Reveal
- Elements fade in as you scroll
- Staggered animation timing
- Intersection Observer for performance

## 🚀 Deployment Options

### 1. Netlify (Free)
1. Create account at [netlify.com](https://www.netlify.com/)
2. Drag and drop your `portfolio` folder
3. Your site is live!

### 2. GitHub Pages (Free)
1. Create a GitHub repository
2. Push your code
3. Enable GitHub Pages in repository settings
4. Access at `username.github.io/repository-name`

### 3. Vercel (Free)
1. Create account at [vercel.com](https://vercel.com/)
2. Import your GitHub repository
3. Deploy with one click

## 📄 License

This project is open source and available for personal and educational use.

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you create something cool, share it!

## 📧 Support

If you have any questions or need help customizing your portfolio, feel free to reach out!

## 🎓 Credits

Created by **GURU PRASATH V**

---

**Happy Coding! 🚀**
