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
-------------------------------------------------
## Tech Stack
- Vite
- Tone.js (Web Audio)
- Vanilla JavaScript

## Author
Developed by **Sarthak**
