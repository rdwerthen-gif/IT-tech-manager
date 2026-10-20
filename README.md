# IT-Tech Consulting – Business Manager

Proper static website layout.

```
website/
├── index.html          # Page shell and navigation
├── css/
│   └── styles.css      # Theme, layout, components, print
├── js/
│   └── app.js          # App logic, data, views, folder sync
├── assets/             # Reserved for images / static files
└── README.md
```

## Run locally

Open `index.html` in Chrome, Edge, Opera, or Brave, **or** from this folder:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

Keep the folder structure intact so `css/styles.css` and `js/app.js` resolve correctly.

## External dependency

- [SheetJS (xlsx)](https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js) – spreadsheet export (CDN in `index.html`)

## Data

- Browser `localStorage` key: `itt`
- Optional disk backup: **Administration & Settings → Local Folder & Data Sync**
  - Auto-save to folder is **on by default** when a folder is connected (toggle on that page)
