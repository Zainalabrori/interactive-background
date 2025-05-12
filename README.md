# 🎆 Interactive Particle Background

A visually engaging and interactive particle background built with **HTML5 Canvas** and **vanilla JavaScript**. Particles respond to mouse/touch movement and dynamically connect to each other. Includes built-in UI controls for real-time customization.

---

## 🌐 Live Demo

[🔗 Visit Live Website](https://zainalabrori.github.io/interactive-background/)

## 🚀 Features

- ✨ Responsive animated background using Canvas
- 🖱️ Interactive: reacts to mouse and touch input
- 🎨 Dynamic color switching
- 🔧 Adjustable particle count, connection distance, and mouse influence
- ⚡ Lightweight: no dependencies

---

## 📂 Project Structure

interactive-background/

├── index.html

├── images/

│ └── favicon.jpg

├── README.md


---

## 📦 Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/Zainalabrori/interactive-background.git
```

### 2. Open in Browser
You can open index.html directly in your preferred web browser. No build step required.

### 🎮 Controls
- Use the control panel at the bottom-left of the screen:
- Reset Particles — Randomizes particle positions
- Change Color — Randomizes particle and line colors
- Particle Count — Adjust between 50 and 500 particles
- Connection Distance — Adjust the max distance for particle connections
- Mouse Influence — Adjust how much particles are pushed away by the mouse

### 🖼️ Preview
Coming soon!

### 🛠️ Customization
You can customize the animation by editing the config object in the JavaScript section of index.html:
```
const config = {
  particleCount: 150,
  particleSize: 3,
  lineDistance: 100,
  mouseRadius: 100,
  particleColor: '#ffffff',
  lineColor: 'rgba(255,255,255,0.2)',
  maxSpeed: 0.5,
  mouseInfluence: 100
};
```

Feel free to add more parameters or link external stylesheets/scripts if needed.

### 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork the repository and submit a pull request.

## ✨ Author

Made with ❤️ by [Zainal Abrori](https://www.linkedin.com/in/zainal-abrori-bb242829b/)
