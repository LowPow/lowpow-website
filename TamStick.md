# TamStick - Tamil Stickers

A static marketing website for **TamStick**, the trending Tamil stickers app by [LowPow](https://lowpow.dev). The site showcases sticker packs, features, and provides download links for the Android app.

## Live Site

- **Website:** [https://tamstick.lowpow.dev](https://tamstick.lowpow.dev)
- **Android App:** [https://play.google.com/store/apps/details?id=com.lowpow.tamiltrollstickers](https://play.google.com/store/apps/details?id=com.lowpow.tamiltrollstickers)

## Stack

- **HTML5** / SCSS / JavaScript (jQuery)
- **Bootstrap** for responsive layout
- **Firebase Hosting** for deployment
- SPA-style routing via Firebase rewrites

## Project Structure

```
tamstick/
├── firebase.json          # Firebase hosting config
├── .firebaserc            # Firebase project mapping
├── .gitignore
├── README.md
└── tamstick/
    ├── index.html         # Homepage
    ├── about.html         # About / other apps
    ├── stickers.html      # Sticker gallery
    ├── privacy.html       # Privacy policy
    ├── terms.html         # Terms & conditions
    ├── scss/              # Source styles (compiled to css/style.css)
    ├── css/style.css      # Compiled stylesheet
    ├── js/script.js       # Main JS
    ├── plugins/           # Vendor assets (Bootstrap, slick, aos, etc.)
    ├── images/            # Images, stickers, backgrounds
    └── stickers.json      # Sticker catalog data
```

## Development

No build step required. Edit files directly under `tamstick/` and deploy.

## Deployment

1. Install Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```

2. Authenticate:
   ```bash
   firebase login
   ```

3. Deploy to Firebase Hosting (site: `tamstick`, project: `lowpow-app`):
   ```bash
   firebase deploy --only hosting:tamstick
   ```

## Contact

- **Email:** contact@lowpow.dev
- **Facebook:** [@LowPowDev](https://facebook.com/LowPowDev)
- **Twitter:** [@LowPowDev](https://twitter.com/LowPowDev)
- **Instagram:** [@LowPowDev](https://instagram.com/LowPowDev)
