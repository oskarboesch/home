# Oskar Boesch - Portfolio Website

A modern, professional portfolio website showcasing your work as a Neuroscience Engineer from EPFL. The site features sections for research, development, music, and photography.

## 🎨 Color Palette

- **Primary Background**: `#F0EEE2` - Warm cream
- **Dark Background**: `#111216` - Deep charcoal
- **Light Accent**: `#E8EEEE` - Soft blue-gray
- **Burgundy**: `#65280B` - Deep wine red
- **Salmon**: `#FF7E81` - Coral pink
- **Peach**: `#F09D5B` - Warm peach

## 📁 File Structure

```
├── index.html       # Main HTML file
├── styles.css       # Styling with your color palette
├── script.js        # Interactive features
├── README.md        # This file
└── assets/          # (Create this folder for images, CV, etc.)
    ├── cv.pdf       # Your CV (add your own)
    └── images/      # Project images
```

## 🚀 Quick Start

### Option 1: Local Development
1. Open a terminal in this directory
2. Run a simple server:
   ```bash
   python3 -m http.server 8000
   ```
   or with Node.js:
   ```bash
   npx http-server
   ```
3. Visit `http://localhost:8000` in your browser

### Option 2: Direct Opening
Simply open `index.html` in your web browser.

## 📝 Customization Guide

### Update Personal Information

**1. Navigation & Contact Info** (`index.html`)
- Update email in contact section: `mailto:your.email@example.com`
- Update LinkedIn, GitHub, and Twitter links

**2. Hero Section**
- Update name and subtitle
- Modify the tagline

**3. About Section**
- Personalize the introduction text
- Update skills categories and items

**4. Projects Section**
- Replace project titles and descriptions
- Add links to your actual projects

**5. CV Section**
- Update education details
- Add your actual experience
- Replace PDF link with your CV path

**6. Social Media Links**
- Update all social links in the contact section and footer

### Add Your Assets

1. Create an `assets` folder in the project directory
2. Add your CV as `cv.pdf`
3. Add project images and other assets

### Customize Colors

All colors are defined in `:root` variables in `styles.css`:

```css
:root {
    --primary-bg: #F0EEE2;
    --dark-bg: #111216;
    --light-accent: #E8EEEE;
    --burgundy: #65280B;
    --salmon: #FF7E81;
    --peach: #F09D5B;
}
```

## ✨ Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Smooth Navigation**: Smooth scrolling and active link highlighting
- **Interactive Elements**: Hover effects, animations, and transitions
- **Modern Typography**: Professional font stack
- **Contact Form**: Ready to be connected to a backend service
- **Mobile Menu**: Hamburger menu for mobile devices
- **SEO Ready**: Semantic HTML structure
- **Accessibility**: Proper heading hierarchy and semantic elements

## 🔧 Further Customization Ideas

### 1. Add Project Galleries
Create individual project pages with more details and image galleries.

### 2. Blog Section
Add a blog to share articles about neuroscience, research, or tech.

### 3. Backend Integration
Connect the contact form to a backend service like:
- Formspree
- EmailJS
- Custom Node.js server

### 4. Analytics
Add Google Analytics or similar to track visitor behavior.

### 5. Dark Mode
Toggle between light and dark themes using JavaScript.

### 6. Performance Optimization
- Optimize images with WebP format
- Lazy load images
- Minify CSS and JavaScript
- Add service worker for offline support

## 📞 Contact Integration

To make the contact form actually send emails, you can use services like:

1. **Formspree** (easiest for static sites)
2. **EmailJS** (client-side solution)
3. **Backend API** (if you have a server)

Example with Formspree:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- form fields -->
</form>
```

## 🌐 Deployment Options

- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Drag-and-drop deployment with form handling
- **Vercel**: Optimized for static and dynamic sites
- **Your Own Server**: Complete control and customization

## 📱 Mobile Optimization

The website is fully responsive:
- Mobile-first design approach
- Touch-friendly buttons and links
- Optimized navigation for small screens
- Readable font sizes on all devices

## ⚡ Performance Tips

1. Optimize all images before uploading
2. Use CSS instead of images when possible
3. Minimize HTTP requests
4. Enable gzip compression on server
5. Use lazy loading for below-the-fold images

## 🎯 Next Steps

1. **Personalize Content**: Replace all placeholder text with your information
2. **Add Assets**: Upload your CV, photos, and project images
3. **Test Responsiveness**: Check on various devices and browsers
4. **Deploy**: Choose a hosting platform and publish
5. **Maintain**: Keep content updated with new projects

## 💡 Tips for Better Results

- Keep content concise and impactful
- Use high-quality images
- Maintain consistent branding
- Update regularly with new projects
- Consider adding testimonials from colleagues

## 📄 License

This template is free to use and modify for your personal use.

---

**Ready to showcase your neuroscience journey?** Update the content and share your portfolio with the world! 🚀
