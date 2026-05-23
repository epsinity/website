# Epsinity — Website 01


## Structure
```
epsinity-site/
├── index.html        ← page content & sections
├── css/styles.css    ← all styles (edit CSS variables at top to retheme)
├── js/main.js        ← nav toggle, form handler, scroll reveal
├── images/           ← all image assets (replace freely)
└── assets/           ← put fonts, icons, downloads here
```

## Run locally
Just open `index.html` in your browser, or serve the folder:
```bash
python3 -m http.server 8000
```
Then visit http://localhost:8000

## Customizing
- **Colors / fonts:** edit the `:root` variables in `css/styles.css`.
- **Content:** edit text directly inside `index.html`.
- **Images:** drop replacements into `images/` keeping the same filenames.
- **Form:** wire `js/main.js` form handler to your email/backend service.
