# Dr. Trupesh Patel - Academic Profile

A modern, responsive academic profile website for Dr. Trupesh Patel, Assistant Professor at Karnavati University. Built with HTML, CSS, and JavaScript. Features research interests, publications, academic background, and professional experience.

## 🌟 Features

- **Modern Academic Design**: Professional UI showcasing research and publications
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Research Timeline**: Interactive timeline for education history
- **Publications Section**: Comprehensive list of conference papers with DOI links
- **Research Interests**: Visual grid displaying areas of expertise
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Lightweight and optimized for performance
- **Easy to Customize**: Well-organized code and comments

## 📁 Project Structure

```
trupesh-academic-profile/
├── index.html              # Main HTML file with all sections
├── assets/
│   ├── css/
│   │   └── styles.css      # All responsive styles
│   ├── js/
│   │   └── script.js       # Interactive functionality
│   └── images/             # Image assets
├── package.json            # Project metadata
└── README.md               # This file
```

## 📋 Website Sections

1. **Hero Section**: Name, title, institution, and research focus
2. **About Me**: Professional summary and statistics
3. **Education**: Timeline of degrees with institution details
4. **Professional Experience**: Work history with key responsibilities
5. **Research Interests**: Visual display of research areas
6. **Publications**: Indexed list of conference papers with DOI links
7. **Contact**: Multiple contact options and academic profiles

## 🚀 Quick Start

### Local Development

1. **Clone or download the repository**
   ```bash
   cd "Trupesh Website"
   ```

2. **Start a local server**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Or using Node.js
   npx http-server
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

## 📝 Customization Guide

### 1. Update Personal Information

Edit `index.html` and replace:
- **Hero Section**: Name, title, institution, and tagline
- **Contact Information**: Email, phone, and location
- **Social Links**: LinkedIn, ResearchGate, Google Scholar, ORCID
- **About Section**: Professional bio and summary

### 2. Update Education

In the Education section of `index.html`, modify:
- Degree types (B.E., M.E., Ph.D.)
- Specializations
- Universities
- Academic achievements (Percentage/CPI)
- Year of completion

### 3. Update Professional Experience

In the Experience section, add/modify:
- Job titles and institutions
- Joining and relief dates
- Key responsibilities as bullet points

### 4. Add Research Interests

In the Research Interests grid section, update:
- Research area icons (using Font Awesome)
- Topic names
- Topic descriptions

### 5. Update Publications

In the Publications section, add new papers:
```html
<div class="publication-item">
    <div class="publication-marker">YYYY</div>
    <div class="publication-content">
        <h3>Paper Title</h3>
        <p class="publication-venue">Conference Name, Location</p>
        <p class="publication-date">Month Year</p>
        <p class="publication-doi"><strong>DOI:</strong> <a href="DOI_LINK">DOI_NUMBER</a></p>
        <span class="publication-badge">Scopus Indexed</span>
    </div>
</div>
```

### 6. Update Styling

Edit `assets/css/styles.css` to customize:
- **Colors**: Modify `:root` CSS variables
- **Fonts**: Change font families
- **Spacing**: Adjust padding and margins
- **Animations**: Modify keyframe animations

## 🌐 Deploy on GitHub Pages

### Prerequisites
- GitHub account
- Git installed locally

### Steps

1. **Create a GitHub repository**
   - Go to https://github.com/new
   - Name it: `trupesh.github.io` (replace with your username)
   - Make it public

2. **Initialize Git**
   ```bash
   cd "Trupesh Website"
   git init
   git add .
   git commit -m "Initial commit: Academic profile website"
   ```

3. **Add remote and push**
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git branch -M main
   git push -u origin main
   ```

4. **Site goes live at**: `https://YOUR_USERNAME.github.io`

## 🔗 External Links

- **Google Scholar**: Link to your Google Scholar profile
- **ORCID**: Open Researcher and Contributor ID
- **ResearchGate**: Research community profile
- **LinkedIn**: Professional networking profile

## 📊 Content Overview

### Key Statistics
- **Experience**: 11+ years in academia
- **Publications**: 8+ Scopus-indexed papers
- **Research Focus**: Federated Learning, Deep Learning, Machine Learning

### Academic Credentials
- Ph.D. (Pursuing) in Computer Science & Engineering
- M.E. in Computer Science & Engineering
- B.E. in Computer Engineering

## ✨ Highlights

- Modern gradient design with professional color scheme
- Smooth scroll animations
- Mobile-responsive hamburger navigation
- Interactive timeline for education
- Publication cards with hover effects
- Direct contact information and social links
- Responsive footer with academic profile links

## 🎨 Design Features

- **Color Scheme**: Professional purple gradient (#667eea to #764ba2)
- **Typography**: Clean, modern fonts
- **Responsive**: Mobile-first design approach
- **Animations**: Smooth fade-in effects on scroll
- **Icons**: Font Awesome integration for visual elements

## 📧 Contact

For questions or updates regarding this website, contact:
- **Email**: trupesh1991@gmail.com
- **Phone**: +91 9714772445

---

**Last Updated**: May 2026

**Option 1: Using Formspree**
1. Go to https://formspree.io
2. Create a new form
3. Update form action in `index.html`:
   ```html
   <form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

**Option 2: Using EmailJS**
1. Sign up at https://www.emailjs.com
2. Install EmailJS: `npm install @emailjs/browser`
3. Initialize and configure in `script.js`

**Option 3: Build a Backend**
- Create a simple Node.js/Express server
- Set up MongoDB/PostgreSQL for storing messages
- Deploy to services like Heroku, Vercel, or AWS

### Add Blog Section

Add a new section in `index.html`:
```html
<section id="blog" class="blog">
    <div class="container">
        <h2 class="section-title">Latest Articles</h2>
        <div class="blog-grid">
            <!-- Add blog posts here -->
        </div>
    </div>
</section>
```

### Add Dark Mode

Uncomment the theme toggle code in `assets/js/script.js` and add dark mode styles to `styles.css`.

## 🎨 Design Features

- **Color Scheme**: Purple gradient with modern aesthetic
- **Typography**: Clean, readable fonts
- **Animations**: Smooth transitions and hover effects
- **Mobile First**: Optimized for all screen sizes
- **Accessibility**: Semantic HTML and keyboard navigation

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Dependencies

This portfolio uses:
- **Font Awesome Icons**: CDN link included
- **No frameworks required**: Pure HTML, CSS, JavaScript
- **Optional**: Python or Node.js for local development

## 📚 Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [JavaScript.info](https://javascript.info/)
- [GitHub Pages Documentation](https://pages.github.com/)

## 🤝 Contributing

If you have improvements, feel free to:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Trupesh**
- GitHub: [@trupesh](https://github.com/trupesh)
- LinkedIn: [linkedin.com/in/trupesh1991](https://www.linkedin.com/in/trupesh1991/)

---

## 🎯 Next Steps

1. **Customize Content**: Update your personal information
2. **Add Projects**: Add your actual projects with links
3. **Setup GitHub Pages**: Follow the deployment steps above
4. **Share**: Share your portfolio with the world!

## 🚀 Performance Tips

- Optimize images: Use tools like TinyPNG
- Minimize CSS/JS: Use minifiers for production
- Enable caching in GitHub Pages
- Use CDN for external resources
- Monitor performance with Google PageSpeed Insights

## ❓ FAQ

**Q: How do I add a custom domain?**
A: In GitHub Pages settings, add your custom domain and update your domain's DNS records.

**Q: Can I use this template commercially?**
A: Yes! The MIT license allows commercial use.

**Q: How do I add a blog section?**
A: See "Advanced Customizations" section above.

**Q: How do I make the contact form work?**
A: Use Formspree, EmailJS, or build a backend (see Advanced Customizations).

---

**Last Updated**: May 2026
**Status**: ✅ Ready for deployment
