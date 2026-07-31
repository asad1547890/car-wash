# ProWash — Premium Doorstep Car Wash & Solar Panel Wash (Faisalabad)

Static site. No build step needed. Includes a Car Wash / Solar Wash service switcher (hero + pricing section) and a mobile sticky Call/WhatsApp bar for higher conversion on phones.

## File structure
```
prowash2/
├── index.html
├── netlify.toml
├── css/
│   └── style.css
├── js/
│   └── main.js
└── assets/
    └── images/
        ├── banner.jpg
        ├── favicon.png
        ├── images__2_.jpg
        ├── images__3_.jpg
        ├── auto-cleaning-before-after.jpg
        └── icon-*.svg
```

## Deploy on GitHub + Netlify

1. Create a new GitHub repo (e.g. `prowash-website`) and push this whole folder
   ```
   git init
   git add .
   git commit -m "ProWash premium website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/prowash-website.git
   git push -u origin main
   ```
2. Go to [app.netlify.com](https://app.netlify.com) → **Add new site → Import an existing project**
3. Connect your GitHub account, select the `prowash-website` repo
4. Build settings: leave **Build command empty**, **Publish directory = `.`** (already set in `netlify.toml`)
5. Click **Deploy site** — done. Netlify gives you a live URL immediately (you can rename it under Site settings → Domain management, e.g. `prowash-faisalabad.netlify.app`)

## Things already wired up
- WhatsApp number: `0343-2250983` (used in nav, hero, packages, floating button)
- Booking form → Formspree endpoint `https://formspree.io/f/mqerlodj`
- All images lazy-load with a smooth fade-in
- Fully responsive (mobile menu included)

## To customize later
- Swap/add gallery photos in `assets/images/` and reference them in `index.html`
- Update coverage-area chips in the `#area` section
- Replace the `#` Facebook link in the footer with your real Facebook Page URL
