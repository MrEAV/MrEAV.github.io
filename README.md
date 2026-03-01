# The Studio — Website

## File Structure

```
art-website/
├── index.html              ← Home
├── pages/
│   ├── about.html
│   ├── artwork.html
│   ├── contact.html
│   ├── workspace.html
│   └── custom-orders.html
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── nav.js
```

## Running Locally

### Option 1 — Python (easiest, no install needed)
```bash
cd art-website
python3 -m http.server 8000
```
Then open: http://localhost:8000

### Option 2 — Node.js (npx)
```bash
cd art-website
npx serve .
```
Then open the URL it gives you.

### Option 3 — VS Code Live Server
Install the "Live Server" extension, right-click `index.html` → Open with Live Server.

> ⚠️ Don't open HTML files directly as file:// URLs — the Google Fonts and some links won't work correctly. Always use a local server.

## Customizing

- **Name / branding**: Search for "The Studio" and "Handcrafted Originals" across all files
- **Colors**: Edit the CSS variables at the top of `assets/css/style.css`
- **Artwork images**: Replace the `.artwork-placeholder` divs in `artwork.html` with real `<img>` tags
- **Contact info**: Update email, Instagram handle, and location in `contact.html`
- **About text**: Replace placeholder copy in `about.html` with your real story
