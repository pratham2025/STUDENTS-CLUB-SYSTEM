<div align="center">

# 🎯 Campus Clubs & Events Portal

Interactive, multi‑page front‑end project showcasing clubs, events, galleries, and utilities — built with plain HTML, CSS, and JavaScript.

[![Made with HTML](https://img.shields.io/badge/HTML-5E5E5E?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Made with CSS](https://img.shields.io/badge/CSS-5E5E5E?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Made with JS](https://img.shields.io/badge/JavaScript-5E5E5E?logo=javascript&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

### ✨ Highlights
- **Multiple themed pages**: Home, Clubs, Events, Blog, Gallery, Contact, and more
- **Small JS utilities & animations**: scrollbars, stars, 3D animation demos
- **Auth scaffolding**: login and registration UI
- **Admin and portal screens**: admin page, discussion, notices
- **Fully static**: runs in any browser — no build step required

---

### 🗂️ Project Structure (selected)

```
prjct/
├─ index.html                # Primary landing page
├─ Homepage.html             # Alternative home variant
├─ project2.html             # Themed landing/layout
├─ coding-club.html          # Club: Coding
├─ Event_mangement-Club.html # Club: Event Management
├─ cricket-club.html         # Club: Cricket
├─ gdsc.html                 # Club: GDSC
├─ blog.html                 # Blog / updates
├─ photo.html                # Photo gallery
├─ contact.html              # Contact page
├─ discussion.html           # Discussion / forum-like page
├─ adminpage.html            # Admin interface UI
├─ loginPortal.html          # Login portal UI
├─ registrationpage.html     # Registration page UI
├─ 3dAnimation.html          # 3D animation demo
├─ scrollbar.html            # Custom scrollbar demo
├─ stars.html                # Starfield animation demo
├─ first.html / new.html / info.html / doct.html  # Misc demos
├─ *.css                     # Stylesheets (style.css, project2.css, ...)
├─ *.js                      # Small scripts (script.js, first.js, ...)
└─ assets (jpg/png/jpeg/svg) # Images & graphics used by pages
```

> Explore the HTML files to browse each section. Many pages are standalone demos you can open directly in the browser.

---

### 🚀 Quick Start

You can open any `.html` file directly in your browser. For best results (and to avoid relative path issues), serve the folder with a lightweight HTTP server:

Option A — Python (built‑in):

```bash
cd prjct
python -m http.server 5500
```

Then visit `http://localhost:5500/index.html` (or any other page).

Option B — Node (no install, via npx):

```bash
npx serve -l 5500 .
```

Option C — VS Code Live Server:
- Open the folder in VS Code → Right‑click `index.html` → "Open with Live Server".

Recommended entry points:
- `index.html`
- `Homepage.html`
- `project2.html`

Club pages to try:
- `coding-club.html`, `Event_mangement-Club.html`, `cricket-club.html`, `gdsc.html`

Utility/Showcase pages:
- `3dAnimation.html`, `scrollbar.html`, `stars.html`, `photo.html`

---

### 🧩 Features in Detail
- **Clean, modular pages**: Each section is a dedicated HTML file with its own styles
- **Animations**: Includes `animate.css`, starfields, scroll effects, and 3D demo
- **Auth UI**: Non‑functional login and registration screens ready for back‑end wiring
- **Admin UI**: Admin template for future moderation/management features
- **Assets**: Rich set of images and icons for a polished look

---

### 🛠️ Tech Stack
- **HTML5/CSS3** for structure and styling
- **Vanilla JavaScript** for interactivity
- Optional **PHP stubs** (`connect.php`, `redirect.php`) present for future integration; pages work without a server

---

### 🔗 Notable Files
- `index.html` — Main entry
- `style.css`, `project2.css`, `first.css`, `registrationpage.css` — Styles
- `script.js`, `first.js`, `scrollbar.js`, `new.js`, `Boolean.js`, `1.js` — Scripts
- `loginPortal.html`, `registrationpage.html` — Auth UI
- `adminpage.html` — Admin UI
- `blog.html`, `contact.html`, `discussion.html` — Content pages

---

### 🧪 Tips & Customization
- Swap hero/background images by replacing files like `bg.jpg`, `codin-club.jpg`, etc.
- Tweak animations in `animate.css` or `stars.css` and `stars.html`.
- Wire up real authentication by integrating the forms in `loginPortal.html` and `registrationpage.html` with your back end.
- Consolidate duplicated pages if shipping to production (the repo includes multiple home/index variants for experimentation).

---

### 📸 Preview

Placeholders below reference existing assets so you can quickly glimpse the design when viewing on GitHub or a renderer that supports images.

![Hero](./bg.jpg)
![Coding Club](./codin-club.jpg)
![Events](./Event_mangement-Club.jpg)

> If images don’t display in your viewer, open the HTML pages locally for the full experience.

---

### 🤝 Contributing
1. Fork the project
2. Create a feature branch: `git checkout -b feat/awesome-thing`
3. Commit changes: `git commit -m "feat: add awesome thing"`
4. Push: `git push origin feat/awesome-thing`
5. Open a Pull Request

Coding style tips:
- Keep HTML semantic, CSS modular, and JS minimal & readable
- Prefer descriptive names over abbreviations
- Test pages by serving over HTTP to catch relative path issues

---

### 📄 License & Assets
- Source code: see the included `License free.txt` and `License premium.txt` for asset usage notes.
- Image and icon assets may have their own licenses. Verify before re‑distribution in public builds.

If you plan to publish, replace any non‑redistributable media with your own or royalty‑free alternatives.

---

### 💡 Roadmap Ideas
- Unify nav/header across pages with shared includes
- Add a site‑wide theme and component library
- Introduce a simple build step (minify, bundle, cache‑bust)
- Connect forms to a real API (login, registration, contact)
- Add accessibility passes and responsive audits

---

Made with ❤️ for learning, showcasing, and experimentation.
