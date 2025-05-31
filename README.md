# 🌍 Multilingual CV Portfolio - Sebastiano De Gobbi

A modern, responsive, and accessible portfolio website showcasing my curriculum vitae in multiple languages.

## 🚀 Features

- **Multilingual Support**: Available in 9 languages (Italian, English, Spanish, German, French, Portuguese, Chinese, Japanese, Korean)
- **Responsive Design**: Optimized for all devices and screen sizes
- **Modern UI/UX**: Clean, professional design with smooth animations
- **SEO Optimized**: Meta tags and semantic HTML structure
- **Accessibility**: Semantic HTML and ARIA labels

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **CSS3**: Modern styling with flexbox, grid, and gradients

## 📁 Project Structure

```
cv-multilang/
├── index.html              # Main landing page with language selection
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
├── rename_files.bat        # Script to rename CV files (Windows)
├── .gitignore             # Git ignore rules
├── LICENSE                # MIT License
└── README.md              # This file
```

## 🌐 Live Demo

Deploy su GitHub Pages quando pronto: `https://seb0t.github.io/cv-multilang/`

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
   - Or use a local server:
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

### Updating Content

- **Personal Information**: Edit the header section in `index.html`
- **Contact Details**: Update the contact section with your information
- **CV Content**: Modify individual language files in the `template/` directory

### Styling

- All styles are contained within each HTML file's `<style>` tag
- The design uses a modern blue gradient theme
- Responsive design with mobile-first approach

## 🔧 Development

### Prerequisites

- Modern web browser
- Git (for version control)
- Text editor or IDE

### File Naming Convention

The project uses dash-separated naming (`cv-en.html`) instead of underscore (`cv_en.html`) for better web standards compliance.

## 📧 Contact

- **Email**: sebastiano.degobbi.pro@gmail.com
- **LinkedIn**: [Sebastiano De Gobbi](https://www.linkedin.com/in/sebastiano-de-gobbi/)
- **GitHub**: [seb0t](https://github.com/seb0t)
- **Location**: Limena (PD), Italia

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

## 📈 Current Features

- ✅ **Responsive Landing Page**: Modern design with language selection
- ✅ **Multiple CV Versions**: 9 language versions with consistent styling
- ✅ **Clean Design**: Professional layout with gradient themes
- ✅ **Cross-browser Compatibility**: Works on all modern browsers
- ✅ **Mobile Responsive**: Optimized for mobile devices
- ✅ **Static Website**: No server-side dependencies

## 🔜 Potential Future Enhancements

- [ ] PWA functionality (service worker, manifest)
- [ ] JavaScript interactivity
- [ ] Analytics integration
- [ ] Dark/light theme toggle
- [ ] Print-friendly CV versions
- [ ] PDF download functionality
- [ ] Language auto-detection based on browser settings

## 🚀 Deployment

### GitHub Pages - Step by Step

#### 1. Preparare il progetto
Prima di tutto, assicurati che i file CV siano rinominati correttamente:
```bash
# Esegui lo script di rinomina se non l'hai già fatto
rename_files.bat
```

#### 2. Creare repository su GitHub
1. Vai su [GitHub.com](https://github.com) e fai login
2. Clicca su "New repository" (pulsante verde)
3. Nome repository: `cv-multilang` 
4. Descrizione: `Professional multilingual CV portfolio`
5. Seleziona "Public" (necessario per GitHub Pages gratuito)
6. **NON** selezionare "Add README" (hai già il tuo)
7. Clicca "Create repository"

#### 3. Collegare il progetto locale a GitHub
Apri il terminale/command prompt nella cartella del progetto e esegui:

```bash
# Inizializza git (se non già fatto)
git init

# Aggiungi tutti i file
git add .

# Primo commit
git commit -m "Initial commit: Multilingual CV Portfolio"

# Collega al repository GitHub (sostituisci 'seb0t' con il tuo username)
git remote add origin https://github.com/seb0t/cv-multilang.git

# Rinomina branch principale (opzionale, ma raccomandato)
git branch -M main

# Carica tutto su GitHub
git push -u origin main
```

#### 4. Attivare GitHub Pages
1. Vai al tuo repository su GitHub
2. Clicca su "Settings" (tab in alto)
3. Scorri fino a "Pages" nel menu laterale sinistro
4. Sotto "Source", seleziona "Deploy from a branch"
5. Seleziona branch "main" e cartella "/ (root)"
6. Clicca "Save"

#### 5. Verifica del deployment
- GitHub mostrerà un messaggio: "Your site is published at https://seb0t.github.io/cv-multilang/"
- Il deployment può richiedere 5-10 minuti la prima volta
- Riceverai una email di conferma quando sarà pronto

#### 6. Aggiornamenti futuri
Per aggiornare il sito dopo modifiche:
```bash
git add .
git commit -m "Descrizione delle modifiche"
git push
```

### Troubleshooting

#### Problemi comuni:
- **404 Error**: Verifica che `index.html` sia nella root del repository
- **File non trovati**: Assicurati di aver rinominato i file CV da `cv_xx.html` a `cv-xx.html`
- **Immagini non visibili**: Controlla che `template/profile-pic_2.png` esista

#### Test locale prima del deploy:
```bash
# Testa con un server locale
python -m http.server 8000
# Vai su http://localhost:8000
```

### Alternative a GitHub Pages

#### Netlify (Raccomandato per facilità)
1. Vai su [netlify.com](https://netlify.com)
2. Drag & drop la cartella del progetto
3. Sito online in 30 secondi!

#### Vercel
1. Vai su [vercel.com](https://vercel.com)
2. Connetti il repository GitHub
3. Deploy automatico ad ogni push

## 📝 Notes

- ✅ **Rinomina i file CV** da underscore a dash prima del deploy
- ✅ **Testa localmente** prima di fare il push
- ✅ **Controlla i link** che tutti i file esistano
- ✅ **Portfolio statico** - nessuna dipendenza server-side necessaria

### Post-Deployment Checklist
- [ ] Sito accessibile all'URL GitHub Pages
- [ ] Tutti i link delle lingue funzionano
- [ ] Immagine profilo visibile
- [ ] Design responsive su mobile
- [ ] Tutti i CV si aprono correttamente

---

⭐ If you found this project helpful, please give it a star!

Made with ❤️ by Sebastiano De Gobbi
