# CodeType

A minimalist typing practice app for programmers. Train your speed and accuracy with real Python and C++ code snippets pulled from classic algorithms and data structures.

![CodeType](https://img.shields.io/badge/built%20with-vanilla%20JS-yellow) ![License](https://img.shields.io/badge/license-MIT-green)

---

## Features

- **60 code snippets** — Python and C++, across Easy / Medium / Hard difficulties
- **Multiple modes** — 15s, 30s, 60s timed runs, or Infinity mode
- **Real-time feedback** — character-by-character highlighting (correct / wrong / active)
- **Live stats** — WPM and accuracy update as you type
- **Sound effects** — keystroke tones, error buzz, and celebration chord (toggleable)
- **Keyboard visualizer** — on-screen keyboard highlights keys as you type
- **Confetti** — triggers at 100+ WPM
- **Dashboard** — full statistics page with charts, analytics, and run history
- **Performance charts** — WPM trend across runs + WPM breakdown within your best run
- **Advanced analytics** — consistency %, improvement trend, fastest/slowest runs

---

## Tech Stack

- **Vanilla HTML / CSS / JavaScript** — no framework, no build step
- **Chart.js 4** — for analytics charts
- **Web Audio API** — synthesized sound effects
- **localStorage** — persistent stats across sessions
- **Google Fonts** — JetBrains Mono + Inter

---

## Getting Started

No installation required. Just open the files in a browser:

```bash
git clone https://github.com/Wasiq2006/codetype.git
cd codetype
open codetype.html   # macOS
# or
xdg-open codetype.html  # Linux
```

Or deploy instantly to [Vercel](https://vercel.com), [Netlify](https://netlify.com), or GitHub Pages — no build step needed.

---

## File Structure

```
codetype/
├── codetype.html     # Main typing application
├── dashboard.html    # Statistics and analytics
├── favicon.svg       # Keyboard icon
└── README.md
```

---

## Keyboard Shortcuts

| Key         | Action                |
| ----------- | --------------------- |
| `Esc`       | Retry current snippet |
| `Tab`       | Insert 4 spaces       |
| `Enter`     | Insert newline        |
| `Backspace` | Delete last character |

---

## License

MIT — feel free to fork and customise.

---

Built by [Wasiq](https://github.com/Wasiq2006)
