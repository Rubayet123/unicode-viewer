# Unicode Inspector – Reveal Hidden Characters

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.mit.org/licenses/MIT)
![Static Badge](https://img.shields.io/badge/Status-Active-brightgreen)
![GitHub last commit](https://img.shields.io/github/last-commit/Rubayet123/unicode-viewer)

**A lightweight, privacy-first web tool to visualize invisible and non-printable Unicode characters in text.**

Live Demo: [https://rubayet123.github.io/unicode-viewer/](https://rubayet123.github.io/unicode-viewer/)

---

## Why This Tool?

When copying text from PDFs, web pages, emails, or databases, **invisible Unicode characters** like zero-width spaces, soft hyphens, or control codes can sneak in and cause:

- Unexpected layout bugs
- Failed string comparisons
- Broken parsing logic
- "Invisible" differences in diffs

This tool **instantly reveals** what’s really in your string.

---

## Features

| Feature | Description |
|-------|-----------|
| **Zero Server Processing** | Runs 100% in your browser — **no data leaves your device** |
| **Real-time Visualization** | See hidden chars as you type or paste |
| **Smart Symbol Replacement** | `CR`, `LF`, `TAB`, `·` for spaces, hex codes for others |
| **Interactive Tooltips** | Hover any character to see Unicode point, hex, and HTML entity |
| **Dark Mode Support** | Auto-detects system preference |
| **Copy & Clear** | One-click actions for workflow efficiency |
| **Live Stats** | Character and byte count |
| **Mobile Friendly** | Works great on phones and tablets |

---

## Screenshots

![Unicode Inspector UI](https://via.placeholder.com/800x450.png?text=Unicode+Inspector+Screenshot)  
*Modern, clean interface with real-time character highlighting*

---

## How to Use

1. **Paste** your suspicious text into the input box
2. **Watch** as invisible characters are replaced with visible symbols
3. **Hover** over any symbol to see detailed Unicode info
4. Use **Copy Output** to export the visualized version

> Example input:  
> `"HelloWorld"` → Shows a **Zero Width Space (U+200B)** between words

---

## Supported Characters

| Symbol | Meaning | Unicode |
|-------|--------|--------|
| `CR` | Carriage Return | `U+000D` |
| `LF` | Line Feed | `U+000A` |
| `TAB` | Horizontal Tab | `U+0009` |
| `·` | Visible Space | `U+0020` |
| `U+200B` | Zero Width Space | `U+200B` |
| `U+00AD` | Soft Hyphen | `U+00AD` |
| `U+2060` | Word Joiner | `U+2060` |
| *Any non-printable* | Shown as hex code | e.g. `U+FFFE` |

---

## Privacy & Security

- **No cookies**
- **No tracking**
- **No IP logging**
- **No data sent to servers**

Your text **never leaves your browser**.

---

## Development & Contribution

### Local Setup

```bash
git clone https://github.com/Rubayet123/unicode-viewer.git
cd unicode-viewer


---
## Contributing
Contributions are welcome! Feel free to:

- Report bugs
- Suggest features
- Improve UI/UX
- Add new character visualizations

Please open an issue first for major changes.

---
## Author
Rubayet
GitHub Profile [https://rubayet123.github.io/](https://rubayet123.github.io/)

---
## License
This project is licensed under the MIT License – see LICENSE for details.
