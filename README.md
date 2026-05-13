# 🤖 Automaton Studio

A visual **DFA / NFA builder and simulator** built with pure HTML, CSS, and Canvas API. No frameworks, no build tools — just open and run.

![Automaton Studio](https://img.shields.io/badge/HTML-5-orange?style=flat-square&logo=html5)
![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript)
![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=flat-square)

---

## 🌐 Live Demo

> **https://github.com/Aniruddh-Saraswat08/Automation-Studio**

---

## ✨ Features

- 🖱️ **Visual canvas editor** — drag and drop states anywhere on screen
- ➕ **Add States** — click to place states on the canvas
- ➡️ **Add Transitions** — drag from one state to another and enter a symbol
- 🔁 **Self-loops** — drag a transition from a state back to itself
- ✅ **Accept & Start states** — right-click or double-click to configure
- 🔀 **DFA and NFA modes** — switch between deterministic and non-deterministic
- **ε-transitions** — supported in NFA mode (type `ε`)
- 🧪 **String simulator** — test any input string instantly
- 👣 **Step-by-step mode** — walk through the computation one character at a time
- ⏵ **Auto-play** — watch the automaton animate through the input
- 🎨 **Neon dark theme** — vibrant purple/green/yellow color scheme

---

## 🚀 Getting Started

### Run Locally
1. Download or clone this repository
2. Open `index.html` in any modern browser
3. That's it — no install needed!

```bash
git clone https://github.com/YOUR-USERNAME/automaton-studio.git
cd automaton-studio
# Open index.html in your browser
```

### Deploy to GitHub Pages
1. Push this repo to GitHub (must be **Public**)
2. Go to **Settings → Pages**
3. Set Branch to `main`, folder to `/ (root)`
4. Click **Save**
5. Your app will be live in ~60 seconds

---

## 🎮 How to Use

| Action | How |
|--------|-----|
| Add a state | Select **Add State** tool → click on canvas |
| Move a state | Select **Select** tool → drag the state |
| Add a transition | Select **Transition** tool → drag from one state to another |
| Set as start state | Right-click state → **Set as Start** |
| Toggle accept state | Double-click state **or** right-click → **Toggle Accept** |
| Delete a state | Right-click state → **Delete** |
| Rename a state | Right-click state → **Rename** |
| Switch DFA ↔ NFA | Click the **Type** button in toolbar |
| Test a string | Type in the input box → click **▶ Test String** |
| Step through | Use **◀ Prev** and **Next ▶** buttons after testing |
| Auto animate | Click **⏵ Auto Play** |
| Load example | Click **Load Example** in toolbar |
| Clear canvas | Click **🗑 Clear** in toolbar |

---

## 📁 Project Structure

```
automaton-studio/
├── index.html        # Entire application (single file)
├── requirements.txt  # No dependencies
└── README.md         # This file
```

---

## 🛠️ Built With

- **HTML5 Canvas** — for drawing states and transitions
- **Vanilla JavaScript** — DFA/NFA simulation engine
- **CSS3** — neon dark theme with glow effects
- **Google Fonts** — JetBrains Mono + Syne

---

## 📐 How the Simulator Works

**DFA mode** — follows exactly one transition per symbol. Rejects if no valid transition exists.

**NFA mode** — tracks all possible active states simultaneously using subset construction. Supports ε-transitions (epsilon/empty string transitions) which are followed automatically.

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 🙋 Author

Made with ❤️ — feel free to fork and improve!
