# minimal-calculator
# 🧮 Minimal Calc

A stylish, fast, and ultra-lightweight dark-themed calculator packaged into a single, fully independent Windows executable (`.exe`).

## ✨ Features
* **Extreme Compactness:** The production-ready `.exe` file is only **442 KB**! It is completely portable and requires no installation.
* **100% Autonomous:** Built without the bloated Chromium engine, meaning it does not carry heavy external `.dll` files around.
* **Persistent History:** The calculator automatically remembers your last calculation even after closing the app (powered by `localStorage`).
* **Keyboard Support:** Full integration for physical keyboard inputs: digits, operators, `Backspace` for character deletion, and `Escape` for instant clear.
* **Pixel Perfect UI:** The window automatically snaps exactly to the boundaries of the calculator upon launch, creating a solid desktop app feel.

## 🛠️ Tech Stack
* HTML5 / CSS3 (Grid Layout, Flexbox)
* Pure JavaScript (Vanilla JS)
* **WebView2 (Microsoft Edge Chromium)** — Native Windows engine utilized for the UI layer.
* **HTML2EXE** — The compiler used to package the web asset into a binary file.

## 🚀 How to Run

### Quick Run (Recommended)
Head over to the **Releases** section on the right, download `Calculator.exe`, and double-click it. It runs out of the box on any modern Windows 10/11 environment.

### Build from Source
If you wish to compile the project yourself:
1. Download the **HTML2EXE** utility (the lightweight edition without the embedded offline engine).
2. Place `index.html` and `HTML2EXE.exe` in the same directory.
3. Open the Command Prompt (`cmd`) in that directory and run:
   ```cmd
   HTML2EXE.exe index.html
<img width="325" height="493" alt="image" src="https://github.com/user-attachments/assets/3a915fb3-3ac3-4bd3-a0c0-00b91dda767f" />

## ☕ Support the Project
If you like this ultra-lightweight calculator and want to help me get a new keyboard, you can support my work here!

[![ko-fi](https://ko-fi.com)]https://ko-fi.com/solyxn
