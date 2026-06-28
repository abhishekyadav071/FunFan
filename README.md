# 🌀 Amazing Project #9 — Animated Fan (HTML, CSS & JavaScript)

A simple yet visually appealing **rotating fan animation** built using pure HTML, CSS, and JavaScript. The fan has a glowing cyan ring, smooth blade rotation, and interactive speed controls.

## 🔗 Live Demo
Open `index.html` in any browser to see it in action.

## ✨ Features
- Glowing cyan ring with neon shadow effect
- Smooth infinite rotation animation using CSS `@keyframes`
- Interactive controls:
  - **ON** → Normal speed (3s rotation)
  - **OFF** → Stops the fan
  - **1 / 2 / 3** → Increases fan speed (1s, 0.5s, 0.1s)
- Speed change handled dynamically via JavaScript `animationDuration`

## 🛠️ Tech Stack
- HTML5
- CSS3 (Keyframe Animations, Flexbox, Box Shadow)
- Vanilla JavaScript (DOM Manipulation)

## 📂 How It Works
```javascript
let a = document.getElementById("img");

function myfunon() {
  a.style.animationDuration = 3 + "s";
}
function myfunoff() {
  a.style.animationDuration = 0 + "s";
}
```
Each button updates the `animationDuration` of the fan element. Since the animation is always running (`infinite` iteration), changing the duration instantly speeds up, slows down, or stops the rotation — no need to start/stop the animation manually.

## 🚀 Run Locally
```bash
git clone https://github.com/abhishekyadav071/FunFan.git
cd FunFan
# Just open index.html in your browser
```

## 👤 Author
**Abhishek Yadav**
- GitHub: [@abhishekyadav071](https://github.com/abhishekyadav071)
- LinkedIn: [abhi-yadav241372](https://linkedin.com/in/abhi-yadav241372)
