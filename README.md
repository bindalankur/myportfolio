# Ankur Bindal - Portfolio Website

A modern, responsive one-page portfolio website showcasing your professional experience as a Certified Scrum Master and QA Lead.

## Features

- 🎨 Modern, clean design with smooth animations
- 📱 Fully responsive - works on all devices
- ⚡ Fast loading with optimized code
- 🎯 Professional sections: Hero, About, Experience, Skills, Contact
- 📄 Direct link to your CV/Resume
- 📧 Contact form with validation
- 🌐 SEO-friendly structure

## Files Structure

```
myport/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
└── Ankur Bindal_CSM_QA Lead_Resume.pdf  # Your CV
```

## Customization Guide

### 1. Personal Information

Edit the following sections in `index.html`:

#### Hero Section (Lines 35-50)
```html
<h1 class="hero-title">Ankur Bindal</h1>
<h2 class="hero-subtitle">Certified Scrum Master & QA Lead</h2>
<p class="hero-description">
    Experienced professional with expertise in Agile methodologies, 
    quality assurance, and team leadership...
</p>
```

#### About Section (Lines 65-85)
Update the about text and statistics:
```html
<div class="stat">
    <h3>5+</h3>
    <p>Years Experience</p>
</div>
```

#### Experience Section (Lines 95-140)
Replace with your actual work experience:
```html
<div class="timeline-content">
    <h3>QA Lead</h3>
    <h4>Your Company Name</h4>
    <p class="timeline-date">2022 - Present</p>
    <ul>
        <li>Your actual responsibilities...</li>
    </ul>
</div>
```

#### Skills Section (Lines 150-200)
Update skills based on your expertise:
```html
<div class="skill-category">
    <h3>Agile & Scrum</h3>
    <div class="skill-items">
        <span class="skill-item">Scrum Master</span>
        <span class="skill-item">Sprint Planning</span>
        <!-- Add your skills -->
    </div>
</div>
```

#### Contact Section (Lines 220-250)
Update your contact information:
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

### 2. Profile Picture

Replace the placeholder in the hero section:
1. Add your profile picture to the project folder
2. Update the hero section in `index.html`:
```html
<div class="hero-image">
    <img src="your-profile-picture.jpg" alt="Ankur Bindal" class="profile-image">
</div>
```
3. Add CSS for the profile image in `styles.css`:
```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

### 3. Colors and Styling

The website uses a blue color scheme. To change colors, edit these CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;
--primary-dark: #1d4ed8;
--gradient-start: #667eea;
--gradient-end: #764ba2;
```

### 4. Contact Form

The contact form currently shows a success message. To make it functional:

1. **For static hosting**: Use a service like Formspree or Netlify Forms
2. **For backend integration**: Replace the form handling in `script.js` with your API calls

Example with Formspree:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
    <!-- form fields -->
</form>
```

## Deployment Options

### 1. GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://username.github.io/repository-name`

### 2. Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Get a custom URL instantly
4. Optionally connect your custom domain

### 3. Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy automatically

### 4. Traditional Web Hosting
Upload all files to your web hosting provider's public_html folder.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize images**: Compress your profile picture and any other images
2. **Minify CSS/JS**: Use online tools to minify for production
3. **Enable compression**: Configure your web server for gzip compression
4. **Use CDN**: The website already uses CDN for Font Awesome and Google Fonts

## SEO Optimization

The website includes basic SEO elements:
- Semantic HTML structure
- Meta tags (add more in the `<head>` section)
- Alt text for images
- Proper heading hierarchy

Add these meta tags to `index.html` for better SEO:
```html
<meta name="description" content="Ankur Bindal - Certified Scrum Master and QA Lead with expertise in Agile methodologies and quality assurance">
<meta name="keywords" content="Scrum Master, QA Lead, Agile, Quality Assurance, Software Testing">
<meta name="author" content="Ankur Bindal">
<meta property="og:title" content="Ankur Bindal - CSM & QA Lead Portfolio">
<meta property="og:description" content="Professional portfolio showcasing expertise in Agile and QA">
<meta property="og:image" content="your-profile-picture-url">
```

## Customization Checklist

- [ ] Update personal information
- [ ] Add your profile picture
- [ ] Update work experience
- [ ] Customize skills and expertise
- [ ] Update contact information
- [ ] Add your actual CV/resume
- [ ] Test on different devices
- [ ] Deploy to your preferred platform

## Support

If you need help customizing the portfolio:
1. Check the HTML comments for guidance
2. Review the CSS classes for styling options
3. Test changes in a local environment first
4. Use browser developer tools to preview changes

## License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Good luck with your portfolio!** 🚀
"# myportfolio" 
