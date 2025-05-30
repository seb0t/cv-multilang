# 🌍 Multilingual CV Portfolio - Sebastiano De Gobbi

A modern, responsive, and accessible portfolio website showcasing my curriculum vitae in multiple languages.

## 🚀 Features

- **Multilingual Support**: Available in 9 languages (Italian, English, Spanish, German, French, Portuguese, Chinese, Japanese, Korean)
- **Responsive Design**: Optimized for all devices and screen sizes
- **Accessibility**: WCAG compliant with screen reader support
- **Modern UI/UX**: Clean, professional design with smooth animations
- **SEO Optimized**: Meta tags and semantic HTML structure
- **PWA Ready**: Progressive Web App capabilities for offline viewing

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Modern styling with flexbox, grid, and gradients
- **Vanilla JavaScript**: Lightweight interactions
- **Progressive Web App**: Service worker for offline functionality

## 📁 Project Structure

```
cv-multilang/
├── index.html              # Main landing page
├── template/
│   ├── cv-it.html          # Italian CV
│   ├── cv-en.html          # English CV
│   ├── cv-es.html          # Spanish CV
│   ├── cv-de.html          # German CV
│   ├── cv-fr.html          # French CV
│   ├── cv-pt.html          # Portuguese CV
│   ├── cv-zh.html          # Chinese CV
│   ├── cv-ja.html          # Japanese CV
│   ├── cv-ko.html          # Korean CV
│   └── profile-pic_2.png   # Profile image
├── assets/
│   ├── icons/              # PWA icons
│   └── images/             # Additional images
├── manifest.json           # PWA manifest
├── sw.js                   # Service worker
├── .gitignore             # Git ignore rules
├── LICENSE                # MIT License
└── README.md              # This file
```

## 🌐 Live Demo

Visit the live portfolio: [GitHub Pages](https://seb0t.github.io/cv-multilang/)

## 📱 Supported Languages

| Language | Code | Status |
|----------|------|--------|
| 🇮🇹 Italian | it | ✅ |
| 🇬🇧 English | en | ✅ |
| 🇪🇸 Spanish | es | ✅ |
| 🇩🇪 German | de | ✅ |
| 🇫🇷 French | fr | ✅ |
| 🇵🇹 Portuguese | pt | ✅ |
| 🇨🇳 Chinese | zh | ✅ |
| 🇯🇵 Japanese | ja | ✅ |
| 🇰🇷 Korean | ko | ✅ |

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/seb0t/cv-multilang.git
   cd cv-multilang
   ```

2. **Open locally**
   - Simply open `index.html` in your browser
   - Or use a local server for full PWA functionality:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using VS Code Live Server extension
   # Right-click on index.html and select "Open with Live Server"
   ```

3. **Visit the application**
   - Open your browser and go to `http://localhost:8000`

## 🎨 Customization

### Adding a New Language

1. Create a new CV file in the `template/` directory (e.g., `cv-ru.html`)
2. Add the language button to `index.html`:
   ```html
   <a href="template/cv-ru.html" class="language-button" lang="ru" aria-label="View CV in Russian">
     <span class="flag" aria-hidden="true">🇷🇺</span>
     <span>Русский</span>
   </a>
   ```
3. Update the service worker cache list in `sw.js`

### Updating Content

- **Personal Information**: Edit the header section in `index.html`
- **Contact Details**: Update the contact section with your information
- **CV Content**: Modify individual language files in the `template/` directory

### Styling

- All styles are contained in `index.html` within the `<style>` tag
- CSS variables can be added for easier theme customization
- The design uses a modern blue gradient theme

### PWA Configuration

- **Icons**: Add your own icons in the `assets/icons/` directory
- **Manifest**: Update `manifest.json` with your details
- **Service Worker**: Modify caching strategies in `sw.js`

## 🔧 Development

### Prerequisites

- Modern web browser
- Local server (optional, for PWA features)
- Git (for version control)

### Building for Production

1. Optimize images (compress and convert to WebP if needed)
2. Minify CSS and JavaScript
3. Test PWA functionality with Lighthouse
4. Deploy to your preferred hosting service

### Testing

- **Accessibility**: Use axe-core or similar tools
- **Performance**: Run Lighthouse audits
- **Cross-browser**: Test on Chrome, Firefox, Safari, Edge
- **Mobile**: Test on various devices and screen sizes

## 📧 Contact

- **Email**: sebastiano.degobbi.pro@gmail.com
- **LinkedIn**: [Sebastiano De Gobbi](https://www.linkedin.com/in/sebastiano-de-gobbi/)
- **GitHub**: [seb0t](https://github.com/seb0t)
- **Location**: Limena (PD), Italy

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/seb0t/cv-multilang/issues).

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📈 Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Load Time**: < 2 seconds
- **Mobile Friendly**: Yes
- **Accessibility**: WCAG 2.1 AA compliant
- **PWA**: Installable and works offline

## 🚀 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://yourusername.github.io/cv-multilang/`

### Other Hosting Options

- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **Surge.sh**: Command-line deployment
- **Firebase Hosting**: Google's hosting solution

---

⭐ If you found this project helpful, please give it a star!

Made with ❤️ by Sebastiano De Gobbi
