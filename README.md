# Ankit Sharma  — Portfolio Website
Generated with **WebGen** (Design System: **Terminal — Dev Mode**)

Congratulations on generating your independent portfolio website! This repository contains a completely standalone, production-ready website with **zero dependencies, no build tools, and no WebGen runtime required**.

---

## 📁 Project Structure

```text
portfolio/
├── index.html        # Semantic HTML5 with SEO meta, OpenGraph tags & accessibility
├── css/
│   └── style.css     # Clean responsive stylesheet with custom CSS variables
├── js/
│   └── script.js     # Minimal vanilla JavaScript for smooth scrolling & interactions
├── assets/           # Folder for images, SVGs, and resume files
└── README.md         # Documentation & deployment guide (this file)
```

---

## 🚀 How to Run Locally

Because this is a pure static website:
1. Simply double-click `index.html` in your file manager to open it in any modern browser (Chrome, Safari, Firefox, Edge, Arc, Brave).
2. Alternatively, if you have Python or Node installed:
   - **Python 3:** `python -m http.server 8000` and visit `http://localhost:8000`
   - **Node (npx):** `npx serve .` or `npx live-server .`
   - **VS Code:** Install the **Live Server** extension and click **Go Live**.

---

## ✏️ How to Edit Your Content

Everything is clean, human-readable vanilla code:

- **Edit Text or Projects:** Open `index.html` in any text editor (VS Code, Sublime Text, Cursor, or Notepad). Search for your name or section headings to update text.
- **Change Colors or Spacing:** Open `css/style.css` and look at the `:root` block at the top of the file. You can easily tweak:
  ```css
  :root {
    --accent: #22C55E;
    /* modify colors, background, and fonts here */
  }
  ```
- **Update Images:** Place your new profile picture or project screenshots inside the `assets/` folder and update the `src=""` attribute in `index.html`.
- **Add Resume:** Save your resume PDF as `assets/resume.pdf` and point your resume link to `assets/resume.pdf`.

---

## 🌐 Free Hosting & 1-Click Deployment

You can host this website completely free of charge with custom domains and automatic SSL:

### Option 1: GitHub Pages (Recommended for Developers & Students)
1. Create a free account at [github.com](https://github.com).
2. Create a new repository named `<your-username>.github.io` (public).
3. Upload all files from this ZIP folder directly to the `main` branch.
4. Go to **Settings** &rarr; **Pages**, ensure source is set to `main` branch / root directory.
5. Your website will be live in ~60 seconds at `https://<your-username>.github.io`!

### Option 2: Netlify (Drag and Drop in 15 seconds)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop this extracted folder into the browser window.
3. Your site is instantly live with a free `.netlify.app` URL and SSL!

### Option 3: Vercel
1. Install Vercel CLI (`npm i -g vercel`) or go to [vercel.com](https://vercel.com).
2. Drag-and-drop the folder or run `vercel` in this directory.

---

## 🎨 Design System Details

- **Template:** Terminal (Dev Mode)
- **Aesthetic:** Systems & Backend Power
- **Primary Accent Color:** `#22C55E`
- **Responsive:** Mobile (<600px), Tablet (600–992px), Desktop (>992px)
- **Print Friendly:** Clean styling for resume printing or PDF export

Built with love by **[WebGen](https://github.com/nirmitAggarwal/webGen)** — The No-Code Portfolio Generator. Star, fork, or contribute on [GitHub](https://github.com/nirmitAggarwal/webGen).
