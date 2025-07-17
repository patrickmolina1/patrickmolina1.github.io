# Patrick Molina - Professional IT Portfolio

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Active-green)](https://patrickmolina1.github.io)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.0+-blue)](https://jekyllrb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A modern, responsive portfolio website showcasing my IT projects, skills, and professional journey. Built with Jekyll and hosted on GitHub Pages.

## 🌟 Live Demo

Visit the live portfolio: [https://patrickmolina1.github.io](https://patrickmolina1.github.io)

## 🚀 Features

### 📱 Modern Design
- Responsive design that works on all devices
- Clean, professional layout optimized for recruiters
- Dark/light theme support
- Smooth animations and transitions
- Loading animations and interactive elements

### 💼 Professional Showcase
- **Featured Projects** - Detailed project pages with technical deep-dives
- **Skills Matrix** - Comprehensive technical skills overview
- **About Page** - Professional background and career goals
- **Contact Section** - Multiple ways to connect
- **Resume Download** - Direct access to PDF resume

### �️ Technical Features
- **SEO Optimized** - Meta tags, structured data, sitemap
- **Performance Optimized** - Fast loading times, optimized images
- **GitHub Integration** - Live GitHub stats and repository links
- **Analytics Ready** - Google Analytics integration support
- **Accessibility** - WCAG compliant design principles

## 📁 Project Structure

```
📦 patrickmolina1.github.io
├── 📁 _layouts/
│   ├── default.html          # Main site layout
│   └── project.html          # Project page layout
├── 📁 _includes/
│   └── navigation.html       # Site navigation
├── 📁 projects/
│   ├── ecommerce-app.md      # E-commerce project
│   ├── data-dashboard.md     # Data analytics project
│   ├── security-toolkit.md   # Cybersecurity project
│   └── cloud-automation.md   # Cloud infrastructure project
├── 📁 assets/
│   ├── 📁 css/
│   │   └── style.scss        # Custom styles
│   ├── 📁 img/               # Images and screenshots
│   └── 📁 files/             # Resume and documents
├── _config.yml               # Jekyll configuration
├── README.md                 # Homepage content
├── about.md                  # About page
├── contact.md                # Contact page
└── index.html                # Site homepage
```

## � Local Development

### Prerequisites
- Ruby 2.5+ 
- Bundler gem
- Git

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/patrickmolina1/patrickmolina1.github.io.git
   cd patrickmolina1.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View in browser**
   Open `http://localhost:4000` in your browser

### Development Commands

```bash
# Serve with live reload
bundle exec jekyll serve --livereload

# Build for production
bundle exec jekyll build

# Serve with draft posts
bundle exec jekyll serve --drafts

# Serve with future posts
bundle exec jekyll serve --future
```

## 📋 Customization Guide

### 1. Personal Information

Update `_config.yml` with your information:

```yaml
title: Your Name
description: Your professional tagline
github_username: yourusername
linkedin_username: your-linkedin
email: your.email@example.com
```

### 2. Profile Image

Add your professional photo:
- Place image in `assets/img/profile.jpg`
- Recommended: 400x400px, square format
- Optimize for web (under 500KB)

### 3. Resume

Add your resume:
- Place PDF in `assets/files/YourName_Resume.pdf`
- Update links in navigation and contact page
- Keep file size under 2MB

### 4. Projects

Each project has its own markdown file in the `projects/` directory:

```yaml
---
layout: project
title: "Project Title"
description: "Brief description"
technologies: ["Tech1", "Tech2", "Tech3"]
demo_url: "https://demo-link.com"
github_url: "https://github.com/yourusername/repo"
---

Project content in markdown...
```

### 5. Colors and Styling

Customize colors in `assets/css/style.scss`:

```scss
// Primary color scheme
$primary-color: #667eea;
$secondary-color: #764ba2;
$text-color: #333;
$background-color: #fff;
```

## 📊 Analytics Setup

### Google Analytics 4

1. Create a Google Analytics 4 property
2. Get your Measurement ID (G-XXXXXXXXXX)
3. Add to `_config.yml`:

```yaml
google_analytics: G-XXXXXXXXXX
```

### GitHub Stats

The portfolio includes live GitHub statistics. Ensure your GitHub profile is public for stats to display correctly.

## 🎨 Adding New Projects

1. Create a new markdown file in `projects/`
2. Use the project layout template
3. Add project images to `assets/img/`
4. Update the main README.md to include the project link

Example project file structure:

```markdown
---
layout: project
title: "New Project"
description: "Project description"
technologies: ["React", "Node.js", "MongoDB"]
duration: "2 months"
status: "Completed"
demo_url: "https://demo.com"
github_url: "https://github.com/user/repo"
---

## Project Overview
Detailed project description...

## Technical Implementation
Technical details...

## Results & Impact
Project outcomes...
```

## 🚀 Deployment

### GitHub Pages (Automatic)

1. Push changes to the `main` branch
2. GitHub Pages automatically builds and deploys
3. Site available at `https://yourusername.github.io`

### Custom Domain (Optional)

1. Add `CNAME` file with your domain:
   ```
   yourdomain.com
   ```

2. Configure DNS records:
   ```
   Type: CNAME
   Name: www
   Value: yourusername.github.io
   ```

## 📱 Browser Support

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile Safari (iOS 12+)
- ✅ Chrome Mobile (Android 8+)

## 🔍 SEO Features

- Semantic HTML structure
- Open Graph meta tags
- Twitter Card support
- JSON-LD structured data
- XML sitemap generation
- Optimized page titles and descriptions
- Image alt text for accessibility

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

This is a personal portfolio, but suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

If you find this portfolio template helpful:

- ⭐ Star this repository
- 🐛 Report issues
- 💡 Suggest improvements
- 🔄 Share with others

## � Resources

### Design Inspiration
- [Dribbble](https://dribbble.com/search/portfolio)
- [Behance](https://www.behance.net/search/projects?search=portfolio)
- [Awwwards](https://www.awwwards.com/websites/portfolio/)

### Development Resources
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Guide](https://pages.github.com/)
- [Markdown Guide](https://www.markdownguide.org/)

### Assets and Tools
- [Unsplash](https://unsplash.com/) - Free professional photos
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography
- [TinyPNG](https://tinypng.com/) - Image optimization

---

**Built with ❤️ by Patrick Molina | IT Student & Aspiring Developer**

*Last updated: {{ site.time | date: "%B %Y" }}*
