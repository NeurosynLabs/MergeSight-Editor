# 🔀 MergeSight Editor

**Smart text merge and comparison tool – Perfect for developers, writers, and content creators**

[![Live Demo](https://img.shields.io/badge/🚀-Live%20Demo-success?style=for-the-badge)](https://neurosynlabs.github.io/MergeSight-Editor/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Stars](https://img.shields.io/github/stars/NeurosynLabs/MergeSight-Editor?style=for-the-badge)](https://github.com/NeurosynLabs/MergeSight-Editor/stargazers)

---

## ✨ Features

- **📝 Merge & Compare**: Merge multiple text files or pasted content effortlessly
- **📄 File Support**: TXT, MD, YAML, JSON, CSV, CSS, JS, HTML, AsciiDoc, Org
- **🔄 Side-by-Side Preview**: Real-time line-by-line alignment between editor and preview
- **🎨 Dark/Light Theme**: Switch themes on the fly
- **💻 Syntax Highlighting**: Highlight code blocks by file type, including inline code
- **📊 Line Matching**: Preview lines stay perfectly synced with editor
- **📋 Easy Export**: Copy merged content or download as a single file
- **🔒 Privacy First**: All processing happens in your browser – no server uploads
- **📱 Responsive**: Works on desktop, tablet, and mobile devices
- **📂 Pop-Out Editor**: Open any file in a dedicated resizable pop-out window
- **⌨ Keyboard Shortcuts**: Common formatting and editor actions with Ctrl/Cmd combinations
- **🔧 Toolbar Actions**: GitHub-like formatting toolbar for Markdown and code

---

## 🚀 Live Demo

**Try it now:** [https://neurosynlabs.github.io/merge-splitter-editor/](https://neurosynlabs.github.io/merge-splitter-editor/)

---

## 🖼 Screenshots / GIFs

![Editor Screenshot](docs/screenshot.png)
![Popout Editor](docs/popout.png)
*Replace placeholders with actual screenshots or GIFs.*

---

## 📖 How to Use

1. **Upload Files**: Drag & drop or select multiple TXT, MD, YAML, JSON, or other supported files
2. **Merge & Edit**: Merge files, edit text inline, and see a synchronized preview
3. **Adjust View**: Toggle dark/light themes, line numbers, and word wrap
4. **Pop-Out**: Open any file in a pop-out window for focused editing
5. **Export**: Copy merged content or download as a single file

---

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Syntax Highlighting**: Highlight.js
- **Hosting**: GitHub Pages
- **Preview Rendering**: Custom JS algorithms for alignment and pop-out synchronization
- **Persistence**: IndexedDB for saving last session files and settings

---

## 📋 Supported File Types

| File Type | Extension | Notes |
|-----------|-----------|-------|
| Markdown | `.md` | Full syntax highlighting |
| Plain Text | `.txt` | Default fallback |
| YAML | `.yml` / `.yaml` |  |
| JSON | `.json` |  |
| CSV | `.csv` |  |
| HTML | `.html` | Inline preview with highlighting |
| CSS | `.css` |  |
| JS | `.js` |  |
| AsciiDoc | `.adoc` |  |
| Org | `.org` |  |

---

## ⌨ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Ctrl/Cmd + B | Bold (`**text**`) |
| Ctrl/Cmd + I | Italic (`*text*`) |
| Ctrl/Cmd + E | Inline code (\`code\`) |
| Ctrl/Cmd + K | Insert link |
| Ctrl/Cmd + 1 / 2 / 3 | Headers (`# H1`, `## H2`, `### H3`) |
| Ctrl/Cmd + Shift + K | Code block (\`\`\`) |
| Ctrl/Cmd + Shift + I | Insert image |
| Ctrl/Cmd + Shift + T | Insert table |
| Ctrl/Cmd + Shift + . | Blockquote (`>`) |
| Ctrl/Cmd + Shift + 8 | Bullet list (`-`) |
| Ctrl/Cmd + Shift + 7 | Numbered list (`1.`) |
| Ctrl/Cmd + S | Export current file |
| Ctrl/Cmd + O | Upload files |
| Ctrl/Cmd + L | Toggle line numbers |
| Ctrl/Cmd + Enter | Toggle fullscreen mode |

---

## ❓ FAQ / Troubleshooting

- **Q:** Why doesn’t syntax highlighting show?  
  **A:** Make sure the syntax highlighting toggle is enabled in the toolbar.

- **Q:** Editor and preview aren’t aligned?  
  **A:** Check if word wrap or line numbers are turned off; toggle them to fix alignment.

- **Q:** Pop-out editor doesn’t sync with main editor?  
  **A:** Only the active file is mirrored; ensure the correct file is active before editing.

- **Q:** Browser support?  
  **A:** Modern Chrome, Firefox, Edge, Safari; IndexedDB may not work on older browsers.

---

## 🔧 Local Development

```bash
# Clone the repository
git clone https://github.com/NeurosynLabs/merge-splitter-editor.git

# Navigate to directory
cd merge-splitter-editor

# Open index.html in your browser
open index.html
