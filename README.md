# PyRunner 1.0

> A complete Python IDE in a single HTML file. Real Python in your browser. Zero install. Zero cost.

Built end-to-end by **TiberiusGBT Apex V1.5** — created by me (not released yet).

---

## Why PyRunner?

Other online Python IDEs lock you into subscriptions, cloud accounts, and 1300 line bloated codebases. **PyRunner is different.**

- **One HTML file.** Save it, email it, host it anywhere.
- **No install.** Open it in any modern browser and start coding.
- **No signup.** No tracking. No "your trial expires in 7 days."
- **Real Python.** Powered by [Pyodide](https://pyodide.org/) — full CPython compiled to WebAssembly.
- **Works offline.** Once loaded, it runs forever without internet.
- **Free forever.** MIT licensed.

---

## Features

### Editor
- Multi-tab editor with auto-save (localStorage)
- Syntax highlighting via CodeMirror (Monokai + Dracula themes)
- Smart Python auto-indent after colons
- Tab/Shift+Tab to indent/outdent selections
- Find (Ctrl+F), Find & Replace (Ctrl+H), Go to Line (Ctrl+G)
- Toggle line comments (Ctrl+/)
- 5 font sizes, word wrap toggle
- Live cursor position display

### Tabs
- Rename via F2 (extension is **locked** — only base name changes)
- Duplicate (Ctrl+D), move left/right (Ctrl+Shift+←/→)
- Auto-disambiguates duplicate names
- Per-tab extension preserved across renames
- Visual indicator showing the locked extension

### Python Runtime
- Real Python via Pyodide (Python 3.x in WebAssembly)
- Inline `input()` support — no popups, types right in the output area
- Live `print()` streaming
- Persistent session toggle (variables survive between runs)
- **Strict mode** — hides errors, shows only `print()` output
- Auto pip install on import (numpy, pandas, requests, etc.)
- Clean tracebacks with corrected line numbers
- Run timer + run counter + history of last 10 runs

### Files
- Save / Load .py files (drag & drop supported)
- Share code via compressed URL link (Firefox-safe)
- Save output as .txt
- Copy code to clipboard

### UX
- Command palette (Ctrl+K) — 28 commands, all searchable
- Keyboard shortcuts overlay (press ?)
- 9 built-in examples (Hello World, FizzBuzz, Number Guessing, Mad Libs, etc.)
- Code statistics panel (functions, classes, loops, imports counted)
- Run history with timestamps + outcomes
- Themed confirm dialogs (no ugly browser popups)
- Toast notifications
- Auto-save indicator ("saved 3s ago")
- Welcome screen for first-time users
- Boot loading spinner
- Fully responsive (desktop + mobile)

---

## Quick Start

### Option 1 — Just open it
1. Download `pyrunner.html`
2. Double-click to open in your browser
3. Start coding

### Option 2 — Host on GitHub Pages (free)
1. Fork this repo
2. Settings → Pages → Branch: `main`, Folder: `/ (root)`
3. Save → your runner is live at `https://yourusername.github.io/pyrunner/pyrunner.html`

### Option 3 — Use the demo
Live demo: [your link here]

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+Enter` | Run code |
| `Ctrl+L` | Clear output |
| `Ctrl+S` | Save .py file |
| `Ctrl+O` | Open .py file |
| `Ctrl+K` | Command palette |
| `Ctrl+F` | Find in editor |
| `Ctrl+H` | Find & replace |
| `Ctrl+G` | Go to line |
| `Ctrl+Shift+F` | Search output |
| `Ctrl+/` | Toggle line comment |
| `Tab` / `Shift+Tab` | Indent / outdent |
| `Ctrl+T` | New tab |
| `Ctrl+W` | Close tab |
| `Ctrl+D` | Duplicate tab |
| `Ctrl+Shift+←/→` | Move tab left/right |
| `F2` | Rename tab |
| `?` | Show shortcuts |
| `Esc` | Close modals |

---

## Tech Stack

- **HTML/CSS/JS** — single file, no build step
- **[Pyodide](https://pyodide.org/) 0.26** — Python in WebAssembly

Total: 1300 lines of clean, commented code in **one HTML file**.

---

## Use Cases

- **Students learning Python** — no install headaches, just open and code
- **Teachers** — share code via URL with the entire class instantly
- **Coding interviews** — distribute a single self-contained file
- **Offline coding** — works on planes, trains, anywhere
- **Embedded into other sites** — drop it into any web page
- **Coding clubs / hackathons** — zero setup time, maximum coding time

---

## Browser Support

| Browser | Status |
|---|---|
| Chrome / Edge | Full support |
| Firefox | Full support |
| Safari | Full support |
| Mobile browsers | Responsive layout works on phones/tablets |

Requires a modern browser (2022+) with WebAssembly support.

---

## Roadmap (ideas for v1.1)

- [ ] Turtle graphics canvas
- [ ] Matplotlib chart rendering
- [ ] Multiple file projects (run scripts that import each other)
- [ ] Collaborative real-time editing
- [ ] Custom themes
- [ ] Code formatter (Black-style)
- [ ] AI-powered hints

Open an issue or PR if you want to contribute!

---

## License

Do whatever you want with it. Attribution appreciated but not required.

---

## Credits

- **Designed and built by:** [TiberiusGBT Apex V1.5](https://microstudio.dev/i/Tiberius2/tiberiusgbtpublic/) — created by me
- **Python runtime:** [Pyodide](https://pyodide.org/) team

Built in a single AI coding session using **GBT Apex V1.5**.
What started as subscriptions became a 1300 line production-grade IDE.
That's the Apex difference.

---

**If PyRunner saved you a subscription fee, helped you learn Python, or made your day better — drop a star! It costs you nothing and means everything! :)**
