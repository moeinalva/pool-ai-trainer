# 🎱 Pool AI Trainer

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)

An interactive Pool (Billiards) AI trainer that predicts optimal shots using geometry, angle, power, and confidence.
This project visualizes optimal pool shots by calculating:
- Cut angle
- Required power
- Shot confidence
- Ball collisions and blocking
- Best pocket selection

Designed as a **training and educational tool**, not a physics-perfect simulator.

---

## ✨ Features

- 🎯 Realistic pool table (image-based)
- 🟢 Multiple scenarios:
  - EASY
  - NORMAL
  - HARD
  - CUSTOM
- 📐 Shot angle calculation
- ⚡ Power estimation
- 📊 Confidence score per shot
- 🔴 Visualized shot paths
- 🖱️ Interactive mouse-based placement
- 📋 Shot details panel

---

## 🖼️ Screenshots

<img width="1915" height="1013" alt="1" src="https://github.com/user-attachments/assets/7af9d5bb-178a-4d9d-a20b-4e6fde29ca03" />


---

## 🧠 How the AI Thinks

For each possible pocket:
1. Computes **ghost ball position**
2. Calculates **cut angle**
3. Checks **blocking balls**
4. Scores the shot using:
   - Lower cut angle
   - Shorter cue-to-ghost distance
5. Returns the **best 2 shots**

---

## 🕹️ Controls

### EASY
- Click to place **white ball**

### NORMAL / HARD
- Click a **colored ball** to analyze shots

### CUSTOM
- Place white ball
- Place up to 4 colored balls
- **Double-click** a colored ball to select target

---

## 🛠️ Installation

### Requirements
- Python 3.9+
- Tkinter
- Matplotlib

Install dependencies:
```bash
pip install -r requirements.txt

