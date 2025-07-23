<p align="center">
  <img src="./assets/gh/thumb.png" alt="openWheels Logo" />
</p>



# openWheels

**openWheels** is a community-led effort to deobfuscate, understand, and restore the original JavaScript/Typescript port of *Happy Wheels*. This project aims to preserve the game's codebase, improve readability, and open the door for learning, modding, and long-term community maintenance.

---
<p align="center">
  <a href="https://discord.gg/Fmb6dHJp5R">
  <img src="./assets/gh/discord.png" alt="Join our discord!" /> </a>
</p>

## 🎯 Project Goals

- ✨ **Readable Code** — Reverse obfuscation to make the codebase human-friendly
- 💾 **Preservation** — Keep the legacy of *Happy Wheels* alive and accessible
- 🔧 **Modding Support** — Enable custom characters, levels, and tweaks

---

## 🗂️ Project Structure

```
openWheels/
├── assets/              # Fonts and game graphics
├── fonts/
├── dependencies.js      # External things (like splitting up sprite sheets, etc.) (we’re deobfuscating this)
├── favicon.ico          # That little Happy Wheels icon
├── happywheels.js       # The original game code (we’re deobfuscating this)
├── index.html           # The main webpage for the game
├── main.js              # Where we hook into and tweak game logic
├── pixi.js              # The rendering engine
├── readme.md            # You're reading it!
├── run.bat              # Quick-launch for Windows
└── style.css            # Basic visual styling
```

---

## 🚀 How to Run It

You can play the game locally in your browser — it’s super easy:

### 🖥️ Quick Start (Windows)

Just double-click `run.bat` and your browser should open it up.

### Or use the command line:
```bash
# Python 3.x
python -m http.server

# Or with Node.js
npx serve .
````

Then visit [http://localhost:8000](http://localhost:8000) (or whatever port your server uses).

---

## 📌 Current Progress

### ✅ Completed
- 🔍 **Initial Deobfuscation** — Code has been beautified and demangled from its minified form
- 🖥️ **Local Execution** — Game successfully runs locally via static hosting
- 🌐 **CORS Proxy Integration** — Connected to the official game server using a CORS proxy

### 🛠️ In Progress
- 🧠 Mapping obfuscated function/variable names to meaningful identifiers
- 🧩 Modularizing key systems (physics, rendering, input, etc.)
- 📜 Writing documentation and architecture notes

---

## 🧠 How You Can Help

We welcome contributions of all kinds:

* Refactor obfuscated code
* Document known functions and class behaviors
* Identify game bugs or rendering issues
* Help modularize the code
* Report findings via Issues or PRs

---

## ⚖️ Legal

> **Disclaimer:** This is a fan-made, educational project. All assets, names, and intellectual property related to *Happy Wheels* are owned by **Jim Bonacci / Fancy Force**. This project does not distribute the original proprietary files and does not claim ownership of the game's content.

We aim to operate under fair use for reverse engineering and preservation.

---

## 📢 Community & Support

Feel free to open issues, start discussions, or suggest features via GitHub.

---

## 🧾 Credits

* **Jim Bonacci / Fancy Force** – Original creator of *Happy Wheels*
* **PIXI.js** – Rendering engine used in the JS port
* **The openWheels team** – Reverse engineering

