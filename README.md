# 🖥️ Tiling Window Manager — From Scratch

> **A handcrafted, minimal, and blazingly fast tiling window manager built from the ground up.**  
> Because real control starts when you write it yourself.  

---

## 🚀 Overview

Tiling Window Manager from Scratch is my journey into **low-level Linux desktop control** —  
no frameworks, no bloated libraries, just raw **X11 magic** and pure customization power.

It’s not “yet another fork” — this is a **scratch-built** environment that’s:  
- 🪶 **Lightweight** — as minimal as possible, without losing usability  
- ⚡ **Fast** — no fancy animations slowing you down  
- 🛠 **Hackable** — tweak every pixel, every shortcut, every behavior  
- 🎯 **Purpose-Built** — made to *stay out of your way* and *let you work*

---

## ✨ Features

- 📐 **Automatic tiling** — no overlapping windows, ever  
- 🎹 **Keyboard-first control** — mouse optional  
- 🔀 **Dynamic layouts** — switch between tile, monocle, and floating modes  
- 💡 **Customizable keybindings** — your workflow, your rules  
- 🖌 **Minimal design** — clean, distraction-free workspace  
- 🧩 **Extensible** — add your own modules with minimal effort  

---

## 📸 Screenshots

| Tiled Layout | Monocle Layout | Floating Layout |
|--------------|----------------|-----------------|
| ![Tiled](docs/screenshots/tiled.png) | ![Monocle](docs/screenshots/monocle.png) | ![Floating](docs/screenshots/floating.png) |

---

## 🛠 Installation

> **Note:** This project is in early development — expect sharp edges 🪓

```bash
# Clone the repo
git clone https://github.com/<your-username>/Tiling-Window-Manager-from-Scratch.git
cd Tiling-Window-Manager-from-Scratch

# Build (example: C)
make

# Run (replace :1 with your X display)
./twm-scratch :1
