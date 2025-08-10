# Avatar Battle Game

[▶ Play Now](https://childweii.github.io/Avatar-Battle-Game/)

**English** | [中文](README_zh-CN.md)

A lightweight, single‑file browser game where two **image avatars** bounce inside an arena, collect power‑ups, and try to knock each other out.  
This project is a clean, from‑scratch rewrite **derived from and inspired by** the original **[Emoji Battle Game](https://github.com/Childweii/Emoji-Battle-Game)**.

> Origin: the idea/mechanics come from the original [Emoji version](https://childweii.github.io/Emoji-Battle-Game/)

---

## What’s new compared to Emoji Battle Game

- **Image Avatars + Square Cropper**  
  Upload any image, then **drag to pan** and **wheel/slider to zoom** in a square viewport. The cropped result is drawn to canvas. No servers involved.

- **Local & Lightweight**  
  Avatars and names stay **only in your browser memory/canvas** — nothing is stored or uploaded.

- **Auto Localization (EN/ZH)**  
  The UI language is determined automatically from `navigator.language` (English or Simplified Chinese).

- **Simplified Start Flow**  
  No team‑picking step. Selecting images and names already defines both sides.

- **Streamlined Result Screen**  
  Only shows the **winner** (or **tie**), cleaner than the original two‑panel layout.

- **Gameplay Parity**  
  Item mechanics are kept on par with the Emoji version. For the full list and detailed effects, **see the [Emoji Battle Game page](https://github.com/Childweii/Emoji-Battle-Game)**:  
  
---

## Quick Start

1. Clone or download this repository.
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox, Safari).  

### How to Play
1. Upload two avatars and (optionally) set short names (≤ 10 chars).
2. Click **Start**.
3. Watch them bounce, pick items, and clash.
4. The **❔** power button occasionally spawns a random item or field effect (with cooldown).

### Localization
- The UI chooses **English** or **Simplified Chinese** automatically based on `navigator.language`.
- No manual toggle is provided to keep the UI minimal.

### Privacy
- No network calls, no storage. All assets live in canvas/memory and disappear on page close/refresh.

---

## Deploy to Your GitHub Pages

1. Push this repo to GitHub (default branch `main`).
2. In **Settings → Pages**, set **Source** to `Deploy from a branch`, **Branch**: `main` / `/ (root)`.
3. Wait for the Pages build; your site will be available at:  
   `https://<your-username>.github.io/<your-repo>/`  
4. Update the **Live Demo** link in this README.

---

## License

This project is released under the **MIT License**. See [`LICENSE`](LICENSE).  
The license includes an attribution notice acknowledging the **Emoji Battle Game** as inspiration.
