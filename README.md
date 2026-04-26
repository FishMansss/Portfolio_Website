# My Portfolio Website

A personal portfolio site built with plain HTML, CSS, and JavaScript.
No frameworks, no build tools — just open in VS Code and edit.

---

## Folder Structure

```
portfolio/
├── index.html          ← Main page (edit your content here)
├── css/
│   └── style.css       ← All styles and theme variables
├── js/
│   └── main.js         ← Scroll animations and nav effects
└── images/             ← Drop any images here (screenshots, profile photo, etc.)
```

---

## How to Run Locally

### Option 1: VS Code Live Server (Recommended)
1. Open VS Code
2. Install the **Live Server** extension (by Ritwick Dey) from the Extensions panel
3. Right-click `index.html` → **"Open with Live Server"**
4. Your browser opens at `http://127.0.0.1:5500` and auto-refreshes on save ✓

### Option 2: Python HTTP Server
Open a terminal in the `portfolio/` folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

---

## How to Customize

### Change your name / info
- Open `index.html`
- Find and replace `Papi` with your real name
- Update the hero subtitle text
- Update the About section paragraph

### Add a new project
Copy this block inside the `<div id="project-grid">` in `index.html`:

```html
<article class="project-card">
  <div class="project-header">
    <span class="project-tag">Language · Topic</span>
    <span class="project-year">2025</span>
  </div>
  <h3>Project Title</h3>
  <p>Short description of what the project does and what you learned.</p>
  <div class="project-footer">
    <a href="https://github.com/yourusername/repo" class="project-link">View Code →</a>
  </div>
</article>
```

### Change the accent color
Open `css/style.css` and change this line at the top:

```css
--accent: #c8f04a;   /* ← swap this hex code */
```

### Add your links
In `index.html`, search for `your@email.com`, `yourusername`, `yourprofile`
and replace them with your real contact info.

---

## Deploying Online (Later)
When you're ready to put this on the internet for free:
- **GitHub Pages** — Push the folder to a GitHub repo, enable Pages in Settings
- **Netlify** — Drag and drop the folder at netlify.com/drop