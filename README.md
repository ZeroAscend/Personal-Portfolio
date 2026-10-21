# ⚔️ CS Portfolio — Elden Ring × Cyber-Anime

A hand-coded personal portfolio website built with pure HTML and CSS — no frameworks, no JavaScript, no templates.

---

## 📁 File Structure

```
portfolio/
│
├── home.html          # Landing page / intro (The Tarnished Dev)
├── projects.html      # Projects page (Artifacts)
├── two.html           # Skills & academics page (Arcane Theory)
├── 404.html           # Custom 404 error page (YOU DIED)
├── webstyle.css       # Global stylesheet — all pages link to this
│
├── cyber-fantasy-header.jpg
├── math-header.jpg
├── pytorch-runes.jpg
├── miku-hologram.jpg
├── bytesized-matrix.jpg
├── lawsuit-aggregator.jpg
└── c-code-snippet.jpg
```

> ⚠️ **All files must be in the same folder.** If `webstyle.css` or any image is in a different location, the page will break or load unstyled.

---

## 🚀 How to Run Locally

No server or install needed. Just:

1. Download or clone this repository
2. Open your file explorer and navigate to the project folder
3. Double-click `home.html` to open it in your browser

> Do **not** paste a file path into your browser manually — always open by double-clicking the file.

---

## 🔗 Page Navigation

| File | Nav Label | Description |
|---|---|---|
| `home.html` | The Tarnished Dev | Introduction & about |
| `projects.html` | Artifacts (Projects) | ML and web projects |
| `two.html` | Arcane Theory (Skills) | C programming & mathematics |
| `404.html` | YOU DIED | Shown on broken/missing links |

---

## 🎨 Design System

**Theme:** Elden Ring dark fantasy × City Pop / cyber-anime  
**Built with:** Vanilla HTML5, CSS3 — no JavaScript, no frameworks

| Token | Value | Used For |
|---|---|---|
| `--grace-gold` | `#d4af37` | Headings, borders, accents |
| `--miku-cyan` | `#33ccff` | Section headings, tags |
| `--neon-pink` | `#ff2d78` | Inline code, highlights |
| `--blood-red` | `#8a0303` | 404 page |
| `--bg-void` | `#07070a` | Page background |
| `--text-bone` | `#e8dece` | Body text |

**Fonts (Google Fonts):**
- `Cinzel` — headings and navigation (Elden Ring style)
- `EB Garamond` — body text
- `Share Tech Mono` — code, footers, tags

---

## 🖼️ Images

All images are local files — replace the placeholder filenames with your own:

| Filename | Used On |
|---|---|
| `cyber-fantasy-header.jpg` | projects.html header |
| `math-header.jpg` | two.html header |
| `pytorch-runes.jpg` | PyTorch project card |
| `miku-hologram.jpg` | Project Miku card |
| `bytesized-matrix.jpg` | ByteSized Media card |
| `lawsuit-aggregator.jpg` | Class Action DB card |
| `c-code-snippet.jpg` | two.html C programming section |

> Pages are designed to render gracefully if images are missing — a gradient fallback is shown in place of the header image.

---

## ✅ Browser Support

Tested in modern browsers. Requires support for:
- CSS Custom Properties
- CSS Grid & Flexbox
- CSS `backdrop-filter` (nav blur — degrades gracefully if unsupported)
- `@keyframes` animations

---

## 📬 Contact

Update the email placeholder across all pages before deploying:

```
your.email@example.com  →  your actual email
```

This appears in the footer of every page and the contact link on `404.html`.

---

*Crafted in the Lands Between — &copy; 2026*
