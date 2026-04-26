# My Portfolio Website

A personal portfolio site built with plain HTML, CSS, and JavaScript.

---

## Folder Structure

```
portfolio/
├── index.html          ← Main page
├── css/
│   └── style.css       ← All styles and theme variables
├── js/
│   └── main.js         ← Empty rn (not visible)
└── images/             ← images here
```

---



### Host 1: VS Code Live Server
1. Open VS Code
2. run the **Live Server** extension (by Ritwick Dey) from the Extensions panel
3. Right-click `index.html` → **"Open with Live Server"**
4. Your browser opens at `http://127.0.0.1:5500` and auto-refreshes on save

### Host 2: Python HTTP Server
Open a terminal in the `portfolio/` folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in browser.

---

## Deploying Online (Later)
- **GitHub Pages** — Push the folder to a GitHub repo, enable Pages in Settings
- **Netlify** — Drag and drop the folder at netlify.com/drop