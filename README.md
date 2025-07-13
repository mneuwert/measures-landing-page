# Measures Landing Page

Static landing page for **Measures** - the ultimate unit converter for iOS.

## Features

- **Multi-language Support**: English, German, Chinese, Japanese with automatic browser detection
- **Responsive Design**: Mobile-first approach using Tailwind CSS
- **App Screenshots**: Dynamic screenshot switching based on selected language
- **Modern Build System**: Tailwind CSS v4 with PostCSS for production-ready CSS

## Development

### Prerequisites
- Node.js (for CSS building)

### Setup
```bash
# Install dependencies
npm install

# Build CSS for development (with watch mode)
npm run dev

# Build CSS for production
npm run build-css-prod

# Serve locally
python3 -m http.server 8000
```

### File Structure
```
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── css/
│   ├── input.css       # Source CSS file
│   └── styles.css      # Generated production CSS
├── js/main.js         # Multi-language functionality
└── images/            # App screenshots and icons
```

## Languages

Screenshots are available in multiple languages:
- `01_en.png`, `02_en.png`, etc. - English
- `01_de.png`, `02_de.png`, etc. - German  
- `01_cn.png`, `02_cn.png`, etc. - Chinese
- `01_jp.png`, `02_jp.png`, etc. - Japanese

## License

© 2025 Measures. All rights reserved.