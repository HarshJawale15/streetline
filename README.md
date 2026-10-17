# 🚕 STREETLINE

**A top-down open-city game in a single HTML file.**
Steal a car, deliver to the red marker, grab coins, and outrun the police, all in your browser with zero installs.

### ▶️ [Play it live](https://harshjawale15.github.io/streetline/)

<!-- Add a screenshot or GIF here:
![Streetline gameplay](screenshot.png)
-->

---

## 🎮 How to Play

You start on foot in a tiny open city. Hop into any car, drive to the **red marker** to complete a delivery, and collect **coins** along the way. Be careful: crashing into cars and people raises your wanted level, and the cops will chase you.

### Goal

| Action | Reward |
|---|---|
| Reach the red delivery marker | **+$250** |
| Pick up a coin | **+$25** |

### Wanted level ★★★★★

- Hitting pedestrians or cars raises your wanted level.
- More stars means more police cars chasing you.
- Break line of sight and stay away from the cops, and your stars slowly fade.
- If your health hits zero you get **wasted**: you respawn and lose **20% of your cash**.

---

## 🕹️ Controls

### Keyboard

| Key | Action |
|---|---|
| `W` `A` `S` `D` / Arrow keys | Walk or drive |
| `E` (or `F` / `Enter`) | Enter or leave a car |
| `Shift` / `Space` | Sprint on foot, handbrake in a car |

### Touch (phones & tablets)

On-screen D-pad plus **E** (enter/exit) and **RUN** buttons appear automatically on touch devices.

---

## 🖥️ HUD

- **Top left:** cash, wanted stars, health bar, and distance to the current marker
- **Top right:** minimap showing the marker, coins, and police (flashing red/blue)

---

## 🚀 Run Locally

No build step, no dependencies.

```bash
git clone https://github.com/HarshJawale15/streetline.git
cd streetline
```

Then open `index.html` in any modern browser. That's it.

---

## 🛠️ Tech

- Plain **HTML + CSS + JavaScript** in one file
- Rendered on the **HTML5 Canvas** (no libraries or frameworks)
- Procedurally generated city blocks, traffic, pedestrians, and police AI
- Responsive layout with keyboard and touch support

---

## 🗺️ Ideas for the Future

- [ ] Sound effects and music
- [ ] More mission types
- [ ] Car upgrades and a shop
- [ ] Saved high scores
- [ ] Day / night cycle

---

## 🤝 Contributing

Found a bug or have an idea? Open an [issue](https://github.com/HarshJawale15/streetline/issues) or send a pull request.

---

## 👤 Author

Made by **[Harsh Jawale](https://github.com/HarshJawale15)**. If you enjoyed the game, leave a ⭐ on the repo!
