# holy-quran-family
Holy Quran Family - Free Quran PWA with offline support

## Home screen (static PWA)

Arabic RTL, navy and gold, mobile-first. No build step, no dependencies.

Files: `index.html`, `styles.css`, `manifest.webmanifest`, `sw.js`, `assets/`.

### Run locally
```
python3 -m http.server 8080
```
Open http://localhost:8080 (service workers need localhost or HTTPS). After the first load the page works offline.

### Deploy to GitHub Pages
Settings → Pages → deploy from branch (`main`, root). All paths are relative, so it works under `/holy-quran-family/`.

Note: `assets/header.svg` is a placeholder for the approved Quran/Kaaba header image; replace it with the final artwork (keep the filename, bump `CACHE` in `sw.js`).
