# Rafiki Global Scholars Website

A modern, responsive website for Rafiki Global Scholars (RGS), a college access program empowering Tanzanian students through mentorship, scholarships, and college preparation programs.

## 🌟 Features

- **Responsive Design**: Mobile-first approach that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Fast Loading**: Optimized static website with minimal dependencies
- **Accessibility**: WCAG 2.1 AA compliant with keyboard navigation support
- **SEO Optimized**: Semantic HTML and meta tags for search engines
- **Interactive Elements**: Animated counters, testimonial slider, contact forms

## 🚀 Quick Start

1. **Clone or download** this repository
2. **Add images** to the `assets/` directory (see Image Requirements below)
3. **Open** `index.html` in a web browser
4. **Deploy** to your hosting platform of choice

## 📁 Project Structure

```
rgs-website/
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # All CSS styles
├── js/
│   └── script.js           # JavaScript functionality
├── assets/
│   ├── logo.png            # RGS logo (add this)
│   ├── favicon.ico         # Website favicon (add this)
│   ├── hero-bg.jpg         # Hero background image (add this)
│   ├── scholars/           # Scholar photos
│   ├── team/               # Team member photos
│   └── news/               # News article images
└── README.md               # This file
```

## 🖼️ Image Requirements

### Required Images to Add:

1. **Logo & Branding**
   - `assets/logo.png` - 200x200px, transparent background
   - `assets/favicon.ico` - 32x32px favicon

2. **Hero Section**
   - `assets/hero-bg.jpg` - 1920x1080px, high-quality background image

3. **Scholar Photos** (in `assets/scholars/`)
   - `featured-scholar.jpg` - 400x400px (Amina Hassan or current featured scholar)
   - `scholar1.jpg` through `scholar4.jpg` - 400x400px each

4. **Team Photos** (in `assets/team/`)
   - `founder.jpg` - 400x500px
   - `program-director.jpg` - 400x500px
   - `mentor-coordinator.jpg` - 400x500px

5. **News Images** (in `assets/news/`)
   - `featured-news.jpg` - 800x600px
   - `scholarship-announcement.jpg` - 800x600px
   - `mentorship-program.jpg` - 800x600px
   - `workshop.jpg` - 800x600px

### Image Sources:
- Use photos from the [RGS Instagram page](https://www.instagram.com/rafikiglobal.scholars/)
- Ensure you have permission to use all images
- Optimize images for web (compress to reduce file size)

## 🎨 Customization

### Colors
The website uses CSS variables for easy color customization. Edit these in `css/styles.css`:

```css
:root {
    --primary-color: #19723a;    /* RGS Green */
    --secondary-color: #ffffff;  /* White */
    --accent-color: #0f5a2e;     /* Dark Green */
    --text-dark: #333;
    --text-light: #666;
    --bg-light: #f8fdf9;
}
```

### Content Updates
- **Contact Information**: Update email addresses and phone numbers in the contact section
- **Social Media Links**: Update Instagram and other social media URLs
- **Scholar Information**: Replace placeholder scholar names and achievements with real data
- **Team Information**: Update team member details and bios
- **Statistics**: Update impact numbers in the hero and impact sections

### Adding New Sections
The website is built with a modular structure. To add new sections:

1. Add HTML structure following the existing pattern
2. Add corresponding CSS styles
3. Update navigation menu if needed

## 🌐 Deployment Options

### Free Hosting Platforms:

1. **Netlify** (Recommended)
   - Drag and drop the `rgs-website` folder to [netlify.com](https://netlify.com)
   - Automatic HTTPS and custom domain support
   - Easy updates via Git integration

2. **GitHub Pages**
   - Push code to a GitHub repository
   - Enable GitHub Pages in repository settings
   - Access via `username.github.io/repository-name`

3. **Vercel**
   - Connect your GitHub repository to [vercel.com](https://vercel.com)
   - Automatic deployments on code changes

### Custom Domain Setup:
1. Purchase a domain (suggested: `rafikiglobalscholars.org`)
2. Configure DNS settings in your hosting platform
3. Enable HTTPS (usually automatic with modern hosts)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ♿ Accessibility Features

- Semantic HTML structure
- ARIA labels where appropriate
- Keyboard navigation support
- High contrast mode support
- Screen reader friendly
- Focus indicators for interactive elements

## 🔧 Technical Details

### Technologies Used:
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **Vanilla JavaScript**: No frameworks, lightweight and fast
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Montserrat, Open Sans, Playfair Display)

### Performance Optimizations:
- Minimal HTTP requests
- Optimized images (when properly compressed)
- CSS and JS minification ready
- Lazy loading for images
- Efficient animations using CSS transforms

## 📊 Analytics & Tracking

To add analytics:

1. **Google Analytics**: Add tracking code to `<head>` section
2. **Facebook Pixel**: For social media tracking
3. **Hotjar**: For user behavior analysis

## 🔒 Security Considerations

- No server-side code (static site = inherently secure)
- HTTPS enabled through hosting platform
- No sensitive data stored in frontend code
- Contact form submissions should be handled securely

## 📈 SEO Optimization

The website includes:
- Meta descriptions and keywords
- Open Graph tags for social sharing
- Structured data markup
- Semantic HTML structure
- Fast loading times
- Mobile-friendly design

## 🛠️ Maintenance

### Regular Updates:
- **Monthly**: Update scholar achievements and news
- **Quarterly**: Review and update statistics
- **Annually**: Refresh photos and major content updates

### Content Management:
- Scholar information is in the HTML file (lines 194-271)
- News updates are in the HTML file (lines 559-667)
- Contact information is in the HTML file (lines 669-758)

## 📞 Support

For technical support or questions about the website:
- Review this README file
- Check the code comments for guidance
- Contact the development team

## 📄 License

This website is created specifically for Rafiki Global Scholars. All rights reserved.

---

**Built with ❤️ for Rafiki Global Scholars**
*Empowering Tanzanian students to reach their dreams*