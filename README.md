
# 🎡 openWheels

**openWheels** is a fan-driven project to bring back the browser version of *Happy Wheels* — in a way that’s clean, understandable, and open to everyone. We’re untangling the original JavaScript/TypeScript code so folks can learn from it, mod it, and keep it alive for the long haul.

---

## 🎯 What We're Aiming For

* ✨ **Readable Code** — Turn that messy obfuscated code into something humans can actually understand
* 💾 **Preserve the Game** — Make sure *Happy Wheels* keeps rolling, even as tech changes
* 🔧 **Modding Power** — Open the doors for new characters, levels, and custom tweaks
* 📚 **Learn by Doing** — Explore how a real, full-featured browser game works under the hood

---

## 🗂️ Project Layout

Here's what you'll find in the repo:

```
openWheels/
├── assets/              # Fonts and game graphics
├── fonts/
├── dependencies.js      # External things (like splitting up sprite sheets, etc.)
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

### 💻 Or use the command line:

```bash
# With Python
python -m http.server

# Or with Node.js
npx serve .
```

Then go to [http://localhost:8000](http://localhost:8000) (or whichever port your server picks).

---

## 📌 Project Status

### ✅ Done

* 🔍 Beautified and cleaned up the original game code
* 🖥️ Runs locally with no issues
* 🌐 Hooked into the official server via a CORS proxy

### 🛠️ Currently Working On

* 🧠 Giving clear names to confusing/obfuscated functions and variables
* 🧩 Breaking big systems (like physics and rendering) into modules
* 📜 Writing up docs so everyone can understand the game’s architecture

---

## 🤝 Want to Help?

We’d love your contributions! Here’s how you can pitch in:

* Clean up and refactor the code
* Document how certain parts of the game work
* Report bugs or strange behavior
* Help split up the monolithic code into smaller, reusable pieces
* Share your findings by opening an Issue or Pull Request

---

## ⚖️ Legal Stuff

> **Disclaimer:** This is a fan-made project created for learning and preservation. All original *Happy Wheels* assets and code are the property of **Jim Bonacci / Fancy Force**.
>
> We don’t distribute any of the original proprietary files and don’t claim ownership of the content. This project is being shared in the spirit of fair use — for education and community preservation.

---

## 🧾 Credits

* 🎮 **Jim Bonacci / Fancy Force** – Creator of *Happy Wheels*
* 🖼️ **PIXI.js** – Rendering engine behind the visuals
* 🔧 **The openWheels community** – Reverse engineering, cleanup, and documentation

---

Got questions? Want to collaborate? Head over to our [GitHub Issues](https://github.com/fvbuk-johnson2254/openWheels/issues) and start the conversation!

