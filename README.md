# FitLife - Modern Fitness Website

A modern, fully responsive, mobile-ready fitness website built with HTML5, CSS3, and JavaScript. FitLife is designed to showcase fitness services, trainers, pricing plans, and provide an engaging user experience across all devices.

## 🚀 Features

### Design & User Experience
- **Fully Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Progressive Web App (PWA)** - Can be installed on mobile devices
- **Accessibility First** - WCAG compliant with keyboard navigation support
- **Fast Loading** - Optimized performance with lazy loading and service workers

### Sections
- **Hero Section** - Compelling call-to-action with animated statistics
- **About Section** - Key benefits and features with animated cards
- **Services Section** - Detailed service offerings with visual cards
- **Trainers Section** - Meet the team with professional profiles
- **Pricing Section** - Clear pricing tiers with feature comparisons
- **Contact Section** - Contact form with validation and contact information

### Technical Features
- **Smooth Scrolling Navigation** - Seamless page navigation
- **Mobile-First Design** - Optimized for mobile devices first
- **Form Validation** - Real-time form validation with user feedback
- **Service Worker** - Offline capabilities and caching
- **Cross-Browser Compatible** - Works on all modern browsers
- **SEO Optimized** - Proper meta tags and structured markup

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and modern web standards
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality and animations
- **Font Awesome** - Icon library for consistent iconography
- **Google Fonts** - Inter font family for modern typography
- **Progressive Web App** - Manifest and service worker for app-like experience

## 📱 Mobile Optimization

- Responsive design that adapts to all screen sizes
- Touch-friendly navigation and buttons
- Optimized images for faster mobile loading
- Mobile-first CSS approach
- PWA capabilities for native app-like experience

## 🎨 Design Features

- **Color Scheme**: Modern gradient design with purple/blue theme
- **Typography**: Inter font family for readability and modern appeal
- **Animations**: Smooth CSS transitions and scroll-triggered animations
- **Layout**: Grid and Flexbox for responsive layouts
- **Icons**: Font Awesome icons for consistent visual language

## 📧 Contact Form

The contact form includes:
- Real-time validation
- Required field checking
- Email format validation
- Service selection dropdown
- Success/error notifications
- Responsive design

## 🔧 Setup & Installation

1. **Clone or download** the repository
2. **Open `index.html`** in a web browser
3. **For development**: Use a local server (like Live Server in VS Code)
4. **For production**: Deploy to any web hosting service

### Development Setup
```bash
# If using VS Code with Live Server extension
# Right-click on index.html and select "Open with Live Server"

# Or use Python's built-in server
python -m http.server 8000

# Or use Node.js http-server
npx http-server
```

### GitHub Pages Deployment

This project includes automated deployment to GitHub Pages using GitHub Actions:

- **Automatic Deployment**: The site is automatically deployed to GitHub Pages on every push to the `main` branch
- **Workflow File**: `.github/workflows/gh-pages.yml` handles the deployment process
- **Live Site**: Once deployed, the site will be available at `https://[username].github.io/fitlife`
- **Manual Deployment**: You can also trigger deployment manually from the Actions tab in GitHub

The deployment workflow:
1. Checks out the code
2. Sets up GitHub Pages configuration
3. Uploads the entire repository as a static site artifact
4. Deploys to GitHub Pages using the `actions/deploy-pages` action

## 📁 File Structure

```
fitlife/
├── index.html          # Main HTML file
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── sw.js              # Service Worker for PWA
├── manifest.json      # PWA manifest file
└── README.md          # Project documentation
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance Optimizations

- **Lazy Loading** - Images load as they come into view
- **Service Worker** - Caches resources for offline use
- **Optimized Images** - Compressed images from Unsplash
- **Minified Resources** - CSS and JS can be minified for production
- **Font Loading** - Optimized Google Fonts loading

## 🎯 SEO Features

- Semantic HTML5 markup
- Meta tags for search engines
- Open Graph tags for social media
- Twitter Card support
- Proper heading hierarchy
- Alt text for images

## 🔄 Customization

### Colors
The main brand colors can be changed in `styles.css`:
```css
/* Primary gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Update these variables throughout the CSS */
```

### Content
- Update text content in `index.html`
- Replace images with your own (maintain aspect ratios)
- Modify services, pricing, and trainer information
- Update contact information

### Styling
- Modify `styles.css` for design changes
- Update fonts in the Google Fonts link
- Adjust animations and transitions

## 📱 PWA Features

The website includes Progressive Web App capabilities:
- App manifest for installation
- Service worker for offline functionality
- Responsive design for mobile
- App-like navigation

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test on multiple devices
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Credits

- Images: [Unsplash](https://unsplash.com)
- Icons: [Font Awesome](https://fontawesome.com)
- Fonts: [Google Fonts](https://fonts.google.com)

## 📞 Support

For support or questions, please contact:
- Email: info@fitlife.com
- Phone: (555) 123-4567

---

Built with ❤️ for the fitness community