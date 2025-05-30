# 🎯 Sebastiano De Gobbi - Professional CV Portfolio

A modern, responsive, and multilingual CV portfolio website showcasing professional experience in AI, Data Science, and Electronics/Telecommunications.

## 🌟 Features

- **Multilingual Support**: 9 languages covering major global markets
- **Professional Design**: Modern gradient design with consistent branding
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **GDPR Compliance**: Appropriate data protection statements for EU markets
- **Easy Navigation**: Homepage with language selection and back-to-home buttons
- **Print-Friendly**: Clean layouts optimized for PDF generation

## 🌍 Available Languages

| Language | File | Market Focus |
|----------|------|--------------|
| 🇮🇹 Italian | `cv_it.html` | Italy (Primary) |
| 🇬🇧 English | `cv_en.html` | Global, UK, USA, Australia |
| 🇪🇸 Spanish | `cv_es.html` | Spain, Latin America |
| 🇩🇪 German | `cv_de.html` | Germany, Austria, Switzerland |
| 🇫🇷 French | `cv_fr.html` | France, Belgium, Canada |
| 🇵🇹 Portuguese | `cv_pt.html` | Portugal, Brazil |
| 🇨🇳 Chinese | `cv_zh.html` | China, Taiwan, Singapore |
| 🇯🇵 Japanese | `cv_ja.html` | Japan |
| 🇰🇷 Korean | `cv_ko.html` | South Korea |

## 📁 Project Structure

```
cv/
├── index.html                 # Homepage with language selection
├── template/
│   ├── cv_it.html            # Italian CV
│   ├── cv_en.html            # English CV
│   ├── cv_es.html            # Spanish CV
│   ├── cv_de.html            # German CV
│   ├── cv_fr.html            # French CV
│   ├── cv_pt.html            # Portuguese CV
│   ├── cv_zh.html            # Chinese CV
│   ├── cv_ja.html            # Japanese CV
│   ├── cv_ko.html            # Korean CV
│   └── profile-pic_2.png     # Profile image
└── README.md                 # This file
```

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for local development)

### Installation
1. Clone or download the repository
2. Place the `profile-pic_2.png` image in the `template/` folder
3. Open `index.html` in your web browser

### Local Development
For local development with a web server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Design Features

### Color Scheme
- **Primary**: Blue gradient (#1e3a8a to #3b82f6)
- **Background**: Purple gradient (#667eea to #764ba2)
- **Text**: Dark gray (#333) for readability
- **Accent**: Various shades of blue for consistency

### Typography
- **Font Family**: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- **Responsive sizing**: Scales appropriately across devices
- **Professional hierarchy**: Clear distinction between headings and content

### Layout
- **Two-column design**: Sidebar with skills, main content with experience
- **Grid-based skills**: Organized skill tags by category
- **Timeline format**: Clear chronological experience presentation

## 📱 Responsive Design

The CV portfolio is fully responsive with breakpoints at:
- **Desktop**: > 768px (Full two-column layout)
- **Tablet/Mobile**: ≤ 768px (Single column, stacked layout)

## 🔧 Customization

### Adding a New Language
1. Copy an existing CV file (e.g., `cv_en.html`)
2. Translate all content to the new language
3. Update the GDPR statement if applicable
4. Add a new button to `index.html` with appropriate flag and language name
5. Update this README with the new language information

### Updating Content
- **Personal Information**: Update contact details in the header section
- **Experience**: Add new positions in the "Work Experience" section
- **Skills**: Update skill tags in the sidebar categories
- **Education**: Add new qualifications in the "Education" section

### Styling Changes
All styles are contained within each HTML file's `<style>` section for easy customization:
- Colors: Update CSS custom properties
- Fonts: Modify the `font-family` declarations
- Layout: Adjust grid layouts and spacing

## 📋 GDPR Compliance

The portfolio includes appropriate GDPR statements for different regions:
- **EU Countries**: Full GDPR authorization statement
- **Non-EU Countries**: Simplified or no statement as appropriate
- **Asian Markets**: EU-style statements for European companies

## 🖨️ Print Optimization

Each CV is optimized for printing/PDF generation:
- Clean layouts without background gradients
- Proper page breaks
- Readable fonts and sizing
- Essential information prioritized

## 📧 Contact Information

- **Email**: sebastiano.degobbi.pro@gmail.com
- **LinkedIn**: [linkedin.com/in/sebastiano-de-gobbi](https://www.linkedin.com/in/sebastiano-de-gobbi/)
- **GitHub**: [github.com/seb0t](https://github.com/seb0t)
- **Location**: Limena (PD), Italy

## 📄 License

This project is for personal use. Feel free to use it as inspiration for your own CV portfolio.

## 🤝 Contributing

This is a personal CV portfolio, but suggestions for improvements are welcome:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📝 Changelog

### Version 1.0.0
- Initial release with 9 language versions
- Responsive design implementation
- GDPR compliance statements
- Homepage with language selection
- Back-to-home navigation buttons

---

**Built with ❤️ GenAi and modern web technologies**
