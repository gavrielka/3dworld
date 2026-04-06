&lt;!-- README.md --&gt;
# Feature World: Random Chaos Edition 🎮🌀

A 3D interactive browser game built with Three.js where you explore a chaotic world filled with surprise effects and colorful collectibles.

![Game Preview](https://img.shields.io/badge/3D-Interactive-blue)
![Tech](https://img.shields.io/badge/Three.js-WebGL-orange)
![Mobile](https://img.shields.io/badge/Mobile-Friendly-green)

## 🎯 Overview

Feature World is a full-screen 3D exploration game featuring:
- A green-headed, brown-bodied character navigating rolling terrain
- Blue sky with floating white clouds
- 30+ colorful chaos objects scattered throughout the world
- Five unique power-up effects that trigger when you touch objects
- Touch controls for mobile + keyboard support for desktop

## 🚀 Quick Start

1. **Download** both files (`index.html` and `README.md`)
2. **Double-click** `index.html` to open in your browser
3. **No installation required** - works entirely in the browser!

Or host it on any static web server (GitHub Pages, Netlify, Vercel, etc.)

## 🎮 Controls

### Mobile/Touch
- **D-Pad** (bottom left): Tap directional buttons to move
- **Jump Button** (bottom right): Tap to jump

### Desktop/Keyboard
- **WASD** or **Arrow Keys**: Move character
- **Spacebar**: Jump

## 🎨 Chaos Objects & Effects

Touch the floating geometric shapes to trigger effects:

| Color | Shape | Effect | Duration |
|-------|-------|--------|----------|
| 🔴 Pink | Cube | **Speed Boost** - 2.5x movement speed | 5s |
| 🟡 Yellow | Sphere | **Slow Motion** - 30% movement speed | 5s |
| 🟣 Purple | Octahedron | **Invisible** - Character becomes transparent | 4s |
| 🟢 Green | Torus | **Chaos Mode** - Random teleport + spawn objects | 3s |
| 🔵 Blue | Cone | **Super Jump** - Launch high into the air | 4s |

## ✨ Features

- **Procedural Terrain**: Rolling hills generated with sine wave algorithms
- **Particle Effects**: Explosion particles when collecting objects
- **Smooth Camera**: Third-person camera follows your character
- **Animated Character**: Walking animation with swinging limbs
- **Effect Stacking**: Multiple effects can be active simultaneously
- **Responsive Design**: Works on mobile, tablet, and desktop
- **No Dependencies**: Only uses Three.js and Tailwind CDN

## 🛠️ Technical Details

### Built With
- **Three.js r128** - 3D graphics library
- **Tailwind CSS** - Utility-first styling
- **Vanilla JavaScript** - No frameworks required

### Browser Compatibility
- Chrome/Edge 80+
- Firefox 75+
- Safari 13+
- Mobile browsers with WebGL support

### Performance
- 60 FPS on modern devices
- Optimized geometry (low-poly models)
- Efficient collision detection
- Responsive touch controls

## 🎲 Game Mechanics

- **Exploration**: Walk freely across the infinite rolling terrain
- **Collection**: Touch chaos objects to trigger surprise effects
- **Chaos**: Effects can stack and combine in unexpected ways
- **Respawn**: Collected objects respawn after 2 seconds elsewhere
- **Random Events**: Occasional ambient notifications add to the chaos

## 📁 File Structure
