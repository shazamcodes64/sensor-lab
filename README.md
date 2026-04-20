# Sensor Lab — Interactive Classroom Presentation

An interactive browser-based presentation covering **LCD**, **Proximity Sensor**, and **IR Sensor** for BEEE Unit 4.

Built to replace traditional PowerPoint slides with live 3D simulations, real-time interactions, and logic-based games.

## Pages

| File | Description |
|------|-------------|
| `index.html` | **Sensor Explorer** — 3D interactive modules for each sensor with live simulations (Three.js) |
| `index2.html` | **System Simulator** — Build INPUT → PROCESS → OUTPUT pipelines for real-world scenarios |
| `index3.html` | **Sensor Logic Simulator** — Engineering-style game with trap scenarios and live mini sims |

## Topics Covered

- **LCD** — Liquid crystals, polarizing filters, voltage control, blocking light principle, advantages/disadvantages
- **Proximity Sensor** — Inductive, capacitive, magnetic, photoelectric types, eddy currents, real-world applications
- **IR Sensor** — Active vs passive IR, LED emitter/receiver, PIR sensors, 38 kHz modulation, applications

## How to Run

1. Download or clone this repo
2. Open any `.html` file directly in a browser (Chrome recommended)
3. No server, no install, no internet required (except for font loading on first open)

## How to Present

1. Open `index.html` — walk through each sensor module, toggle the 3D simulations live
2. Open `index3.html` — run the logic simulator as a class activity, let students vote before clicking "Run System"
3. Use the trap scenario (LCD as input sensor) to spark discussion

## Tech Stack

- Vanilla HTML/CSS/JavaScript
- Three.js r128 (CDN) for 3D simulations
- Google Fonts (Orbitron, Inter, JetBrains Mono)
- Zero frameworks, zero build step

## License

Free to use for educational purposes.
