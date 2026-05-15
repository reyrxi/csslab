# CSSLab

Live HTML/CSS editor with Tailwind support. Write, preview and export in seconds.

**[reyrxi.github.io/csslab](https://reyrxi.github.io/csslab)**

---

## Features

- **Live preview** — updates as you type, no refresh needed
- **Tailwind CDN** — use any Tailwind class out of the box
- **6 starter templates** — Hero, Card, Form, Navbar, Grid, Blank
- **Viewport switcher** — Desktop, Tablet and Mobile preview
- **Snapshot history** — save versions and restore anytime
- **Session restore** — picks up where you left off on reload
- **Share via URL** — encode your work into a shareable link
- **Export** — download as a standalone `.html` file
- **Keyboard shortcuts** — fast, no-mouse workflow
- **Zero dependencies** — single file, no build step, no npm

---

## Usage

```bash
git clone https://github.com/reyrxi/csslab
cd csslab
open index.html   # macOS
start index.html  # Windows
```

Or just open `index.html` directly in any browser.

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+S` | Save snapshot |
| `Ctrl+Enter` | Force refresh preview |
| `Ctrl+Shift+C` | Copy active editor code |
| `Ctrl+Shift+E` | Export HTML file |
| `Ctrl+1` | Switch to HTML tab |
| `Ctrl+2` | Switch to CSS tab |
| `Esc` | Close panels |

---

## Tech

Pure HTML, CSS and vanilla JavaScript. Tailwind is loaded via CDN inside the preview iframe only. Syntax highlighting via CodeMirror 5.

---

## License

MIT
