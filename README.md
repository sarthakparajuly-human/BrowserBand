# 🎸 Browser Band

A browser-based virtual music studio. Play drums, piano, and xylophone using your keyboard or mouse. Record your jams and export them!

## Features
- 🥁 **Drums** - Keys: A (kick), S (snare), D (hi-hat)
- 🎹 **Piano** - Keys: Z, X, C, V, B, N, M, comma
- 🎼 **Xylophone** - Keys: 1-8
- ⏺️ **Recording** - Record up to 30 seconds and export as audio

## Quick Start

### Option 1: Use the built version (No installation needed!)
The `docs/` folder contains a ready-to-deploy build. You can:
- Open `docs/index.html` directly in your browser
- Or use a simple local server (see below)

### Option 2: Run locally with Python (No Node.js required!)
If you have Python installed, you can start a local web server:

**Python 3:**
```bash
cd docs
python -m http.server 8000
```

**Python 2:**
```bash
cd docs
python -m SimpleHTTPServer 8000
```

Then open http://localhost:8000 in your browser.

### Option 3: Run with Vite dev server
```bash
npm install
npm run dev
```

---

## 🚀 Deploy to GitHub Pages

1. **Push your code to GitHub** (make sure the `docs/` folder is committed)

2. **Go to your repository Settings** → **Pages**

3. **Under "Build and deployment":**
   - Source: **Deploy from a branch**
   - Branch: Select your branch (e.g., `main`) and folder: `/docs`
   - Click **Save**

4. Your site will be live at `https://sarthakparajuly-human.github.io/BrowserBand/`

### Alternative: Using GitHub Actions
You can also use GitHub Actions for automatic deployment. The `docs/` folder is already built with relative paths (`./`) so it works on any subdirectory.

---

## Tech Stack
- Vite
- Tone.js (Web Audio)
- Vanilla JavaScript

## Author
Developed by **Sarthak**
