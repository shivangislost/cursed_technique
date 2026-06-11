# SAT0RU — Cursed Technique Visualizer

A real-time cursed technique visualizer inspired by Jujutsu Kaisen. Uses hand-tracking via your webcam to trigger stunning particle-based cursed techniques powered by Three.js and MediaPipe.

## Features


Hand gestures control 20,000 particles to render volume-based cursed techniques:

- **Cursed Technique Reversal: Red** — A violent, spiraling vortex of repulsive force.
  - *Trigger:* Index finger pointing up.
- **Domain Expansion: Infinite Void** — A celestial domain with a bright event horizon ring and deep cosmos.
  - *Trigger:* Index + Middle fingers up.
- **Secret Technique: Hollow Purple** — A chaotic singularity combining attraction and repulsion.
  - *Trigger:* Pinch gesture (Thumb + Index touching).
- **Domain Expansion: Malevolent Shrine** — A dark, ominous shrine structure.
  - *Trigger:* All fingers up (open hand).

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Edge, Firefox)
- A webcam

### Run Locally
1. Clone the repo
   ```bash
   git clone https://github.com/shivangislost/cursed_technique.git
   cd cursed_technique
   ```
2. Serve with any static server
   ```bash
   python3 -m http.server 8080
   ```
3. Open `http://localhost:8080` in your browser and allow camera access.

## Tech Stack
- [Three.js](https://threejs.org/) — 3D particle rendering & bloom post-processing
- [MediaPipe Hands](https://google.github.io/mediapipe/) — Real-time hand tracking

## Author

**Shivang**
