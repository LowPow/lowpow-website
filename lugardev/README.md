# Lugar - The Blaster Website

This is a Bootstrap 5 + Sass project that serves as the official website for Lugar apps. The site features:
- Hero section with app introduction
- Product showcase for StickBook and Digitalize
- User testimonials carousel
- App store download links
- Responsive navigation and footer

## Tech Stack

- **HTML5** - Semantic markup
- **Bootstrap 5.0** - CSS framework
- **Sass/SCSS** - CSS preprocessing with modular architecture
- **FontAwesome 5** - Icons
- **GLightbox** - Lightbox gallery

## Project Structure

```
lugardev/
├── index.html                 # Main HTML file
├── package.json               # NPM configuration
├── scss/                      # Sass source files
│   ├── style.scss             # Main entry point
│   ├── _custom.scss           # Custom variables & overrides
│   ├── fontawesome.scss       # FontAwesome imports
│   ├── components/            # Reusable components
│   │   ├── _animations.scss
│   │   ├── _buttons.scss
│   │   ├── _mixins.scss
│   │   └── _typography.scss
│   └── sections/              # Page sections
│       ├── _campanies.scss
│       ├── _faq.scss
│       ├── _footer.scss
│       ├── _get-started.scss
│       ├── _intro-section.scss
│       ├── _navbar.scss
│       ├── _portfolio.scss
│       ├── _services.scss
│       └── _testimonials.scss
├── assets/
│   ├── css/                   # Compiled CSS output
│   │   ├── style.css
│   │   └── fontawesome.css
│   ├── js/                    # JavaScript libraries
│   │   └── bootstrap.bundle.min.js
│   ├── vendors/               # Third-party libraries
│   │   └── glightbox/
│   └── webfonts/              # Font files
└── images/                    # Image assets
    ├── arts/
    ├── products/
    └── stores/
```

## Getting Started

### Prerequisites

- Node.js (v14+)
- npm

### Installation

```bash
npm install
```

### Development

Compile Sass with watch mode:

```bash
npm run compile:sass
```

This watches `scss/` directory and compiles to `assets/css/` on changes.

## Features

| Section | Description |
|---------|-------------|
| **Navbar** | Fixed top navigation with responsive collapse menu |
| **Hero/Intro** | "Lugar the Blaster" branding with CTA to apps |
| **Products** | Two apps: StickBook (WhatsApp stickers) & Digitalize |
| **Testimonials** | Carousel with user feedback |
| **Get Started** | Google Play store link |
| **Footer** | Company info, app links, contact, social media |

## Apps Featured

1. **StickBook** - Tamil Trending Stickers for WhatsApp
   - [Website](https://lowpow.dev/stickbook/)
   - [Google Play](https://play.google.com/store/apps/dev?id=8274773791426925010)

2. **Digitalize** - Make it Simple
   - [Google Play](https://play.google.com/store/apps/details?id=com.lugar.digitalize)

## Customization

Modify `scss/_custom.scss` for:
- Color variables
- Spacing scales
- Typography settings
- Bootstrap overrides

## Deployment

The compiled assets in `assets/css/` and `assets/js/` are production-ready. Deploy the entire folder to any static hosting (Netlify, Vercel, GitHub Pages, etc.).

## License

ISC License - See package.json for details.

## Author

**Patrick Muriungi** - [lowpow.dev](https://lowpow.dev)