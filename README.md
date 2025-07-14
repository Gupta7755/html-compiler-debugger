# 🚀 Smart HTML Compiler & Live Debugger 🔍

A web-based tool that allows users to write, format, debug, and preview HTML code instantly. It features auto-indentation, real-time syntax error detection, and a live browser preview panel — ideal for learners, developers, and educators.

---

## 🧠 Features

- 📝 **Code Editor** powered by [CodeMirror](https://codemirror.net/)
- ✨ **Auto-Indentation** using `js-beautify` for cleaner HTML
- 🐞 **Real-Time Error Detection**:
  - Detects unclosed tags
  - Identifies mismatched tags
  - Highlights line numbers for debugging
- 🌐 **Live Preview Panel** to render the HTML output on the fly
- 🎛️ **Responsive UI** with dark-themed editor and debug console
- 🧹 **Clear Button** to reset the code and output
- 📋 Built with pure **HTML, CSS, and JavaScript**

---

## 📸 UI Layout

- **Left Panel:** HTML Code Editor
- **Right Panel:**
  - 🔧 Debug Console (Top)
  - 🌍 Live Rendered Output (Bottom)

---

## 🧩 Tech Stack

| Technology      | Purpose                         |
|-----------------|---------------------------------|
| HTML/CSS/JS     | Core Structure and Logic        |
| CodeMirror      | Code editor with syntax support |
| js-beautify     | HTML auto-formatting            |
| DOMParser       | Syntax error analysis           |
| iframe[srcdoc]  | Inline HTML rendering           |

---

## 📦 Installation (for local testing)

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/html-compiler-debugger.git
