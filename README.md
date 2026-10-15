# 🏔️ Terrain Sculptor — 3D Procedural Terrain Generator

> An interactive 3D WebGL application built with Three.js, Express, and Simplex Noise that algorithmically generates and sculpts realistic 3D procedural terrain in real time.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

---

## 🌟 Overview

**Terrain Sculptor** is a web-based procedural generation tool that renders 3D landscape meshes directly in the browser. By leveraging **Three.js** for WebGL rendering and **Simplex Noise** algorithms, users can manipulate mathematical terrain parameters in real time to generate endless unique landscape variations.

---

## ✨ Key Features

* **Real-time 3D Mesh Generation:** Renders 3D terrain geometry dynamically utilizing WebGL via Three.js.
* **Procedural Noise Algorithms:** Uses Multi-octave **Simplex Noise** paired with the **Alea** PRNG engine to create natural-looking landforms, mountain peaks, and elevation maps.
* **Interactive Parameter Tuning:** Powered by **Tweakpane**, allowing users to fine-tune parameters on the fly:
  * **Frequency:** Controls the scale/size of terrain features.
  * **Elevation:** Controls peak heights.
  * **Octaves:** Layered noise passes for high-frequency surface detail.
  * **Smoothing:** Algorithmic post-processing passes to soften terrain edges.
  * **Seed:** Generates deterministic terrain layouts.
* **Camera Orbit Controls:** Full 360° pan, tilt, drag, and zoom navigation.

---

## 🛠️ Tech Stack

* **3D Graphics & Rendering:** Three.js (WebGL)
* **Algorithms:** Simplex Noise, Alea (Seedable PRNG)
* **UI & Controls:** Tweakpane, Custom CSS (IBM Plex Mono / Fraunces typography)
* **Backend / Server:** Node.js, Express.js

---

## 🚀 Getting Started

### Prerequisites
* [Node.js](https://nodejs.org/) (v16 or higher)

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/chpietrusewicz/a4-creativecoding.git](https://github.com/chpietrusewicz/a4-creativecoding.git)
   cd a4-creativecoding
