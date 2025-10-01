# Video Player — HTML/CSS/JS

A lightweight HTML5 **video player** built with plain **HTML**, **CSS**, and a small bit of **JavaScript**. Ideal for experimenting with custom controls and basic theming.  
License: **GPL-3.0**. :contentReference[oaicite:1]{index=1}

---

## ✨ What’s inside
- Static page with an HTML5 `<video>` element
- Custom styles in `styles.css`
- Minimal JS hooks in `script.js` for player behavior
- Simple, no-build setup (open in a browser or use any static server)  
Repo layout and license match the files shown on GitHub. :contentReference[oaicite:2]{index=2}

---

## 🗂️ Project structure
```
.
├─ index.html
├─ styles.css
├─ script.js
└─ LICENSE # GPL-3.0
```

---

## 🚀 Getting started

### 1) Clone
```bash
git clone https://github.com/hakimmurphy/videoplayer.git
cd videoplayer
```

### 2) Add a sample video
Place an .mp4 (or other supported format) somewhere accessible and point the <source> in index.html to it, for example:
```
<video id="player" controls>
  <source src="media/sample.mp4" type="video/mp4" />
  Your browser does not support the video tag.
</video>
```

### 3) Run locally
- Easiest: open index.html directly in your browser, or
- Serve the folder with any static server, e.g. Python:
```
python3 -m http.server 5500
# visit http://localhost:5500
```

---

## 🛠️ Customize
- Tweak layout/colors in styles.css
- Extend behavior in script.js (e.g., keyboard shortcuts, custom buttons)
- Add multiple <source> tags for different encodings (mp4/webm)

---

## 🛣️ Roadmap (ideas)
- Play/Pause/Seek buttons with custom SVG icons
- Volume slider & mute toggle
- Fullscreen toggle and playback speed control
- Progress bar with buffered/played indicators
- Accessibility: focus states, ARIA labels, keyboard controls

---

📄 License
GPL-3.0.

---

## 🗣️ Author
Hakim Murphy



