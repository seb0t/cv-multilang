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
- **Vanilla JavaScript**: PWA functionality and user interactions
- **Progressive Web App**: Service worker for offline functionality

## 📁 Project Structure

```
cv-multilang/
├── index.html              # Main landing page with language selection
├── template/
│   ├── cv-it.html          # Italian CV (to be renamed from cv_it.html)
│   ├── cv-en.html          # English CV (to be renamed from cv_en.html)
│   ├── cv-es.html          # Spanish CV (to be renamed from cv_es.html)
│   ├── cv-de.html          # German CV (to be renamed from cv_de.html)
│   ├── cv-fr.html          # French CV (to be renamed from cv_fr.html)
│   ├── cv-pt.html          # Portuguese CV (to be renamed from cv_pt.html)
│   ├── cv-zh.html          # Chinese CV (to be renamed from cv_zh.html)
│   ├── cv-ja.html          # Japanese CV (to be renamed from cv_ja.html)
│   ├── cv-ko.html          # Korean CV (to be renamed from cv_ko.html)
│   └── profile-pic_2.png   # Profile image
├── manifest.json           # PWA manifest
├── sw.js                   # Service worker
├── rename_files.bat        # Script to rename CV files
├── .gitignore             # Git ignore rules
├── LICENSE                # MIT License
└── README.md              # This file
```

## 🌐 Live Demo

Visit the live portfolio: [GitHub Pages](https://seb0t.github.io/cv-multilang/) *(deploy when ready)*

## 📱 Supported Languages

| Language | Code | File Status |
|----------|------|-------------|
| 🇮🇹 Italian | it | ✅ Available |
| 🇬🇧 English | en | ✅ Available |
| 🇪🇸 Spanish | es | ✅ Available |
| 🇩🇪 German | de | ✅ Available |
| 🇫🇷 French | fr | ✅ Available |
| 🇵🇹 Portuguese | pt | ✅ Available |
| 🇨🇳 Chinese | zh | ✅ Available |
| 🇯🇵 Japanese | ja | ✅ Available |
| 🇰🇷 Korean | ko | ✅ Available |

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/seb0t/cv-multilang.git
   cd cv-multilang
   ```

2. **Rename CV files (if needed)**
   - Run `rename_files.bat` on Windows to convert from underscore to dash naming
   - Or manually rename files from `cv_xx.html` to `cv-xx.html`

3. **Open locally**
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

4. **Visit the application**
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
- The design uses a modern blue gradient theme
- Responsive design with mobile-first approach

### PWA Configuration

- **Icons**: Currently uses profile image as icon (can be enhanced with dedicated PWA icons)
- **Manifest**: Update `manifest.json` with your details
- **Service Worker**: Modify caching strategies in `sw.js`

## 🔧 Development

### Prerequisites

- Modern web browser
- Local server (optional, for PWA features)
- Git (for version control)

### File Naming Convention

The project uses dash-separated naming (`cv-en.html`) instead of underscore (`cv_en.html`) for better web standards compliance.

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

## 📈 Features Implemented

- ✅ **Responsive Landing Page**: Modern design with language selection
- ✅ **PWA Support**: Manifest and service worker for offline functionality
- ✅ **Accessibility**: ARIA labels, semantic HTML, reduced motion support
- ✅ **SEO Optimization**: Meta tags, Open Graph, Twitter Cards
- ✅ **Modern Styling**: CSS Grid, Flexbox, gradients, smooth animations

## 🔜 Future Enhancements

- [ ] Dedicated PWA icons in multiple sizes
- [ ] Analytics integration
- [ ] Dark/light theme toggle
- [ ] Print-friendly CV versions
- [ ] PDF download functionality
- [ ] Language auto-detection based on browser settings

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

## 📝 Notes

- Make sure to rename CV files from underscore to dash format before deployment
- Test PWA functionality with a local server
- All CV content files are in the `template/` directory

---

⭐ If you found this project helpful, please give it a star!

Made with ❤️ and GenAi 
