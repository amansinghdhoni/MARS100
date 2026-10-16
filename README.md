# ☄ MARS 100: Survival Protocol

> Your ship crashed on Mars. Farm, find water, fix the rocket and survive **21 days** to fly home!

A single-file 3D survival game that runs in your browser. No install, no build step. Drag cards onto a 3D Mars world, keep your base alive, and escape before Day 21.

**🎮 Play it here:** `https://<your-username>.github.io/<your-repo-name>/`  *(replace after enabling GitHub Pages)*

---

## ✨ Features

- 🌍 **Real 3D Mars**: crashed ship, domes, solar panels, walls and sand storms. Drag to look around, scroll to zoom.
- 📖 **21-day story**: radio calls, a big sandstorm, fever, solar flares, a lost rover and more.
- 🔗 **Linked resources**: more food needs more water, more water needs more power, and storms hide the sun.
- 🔬 **Tech tree**: five permanent upgrades you buy with parts.
- 🧩 **Rocket parts**: collect an Engine, a Heat Shield and a Guidance Chip.
- 👽 **Alien mystery**: study the Ancient Ruins to find a hidden gate and a secret ending.
- 🔊 **Sound**: synthesized wind, clicks, thunder, rocket launch and ambient music (no audio files).
- 🏆 **Achievements** saved on your device.
- 🎓 **Guided tutorial** on Day 1.
- 💾 **Save and resume**: continue after closing the page.
- 🎬 **Movie scenes** (can be turned off in Settings) and 3 difficulty levels.

---

## 🕹 How to play

1. Type your name and start. A short guided tutorial teaches the basics on Day 1.
2. **Drag a card** from the bottom bar onto the Mars world (double-tap a card to auto-place it). You get a few moves each day.
3. Press **⏭ GO TO NEXT DAY** when you are done.
4. Read the **yellow helper line**. It tells you what to do next.

### Where to drop each card

| Card | Drop it on |
|---|---|
| 🔧 Find parts | the crashed ship |
| 🧊 Find water, 🛡️ Walls | the Mars ground |
| 🌱 Garden, ☀️ Sun panel, ⛏️ Water maker | an empty spot on the ground |
| 🛠️ Fix rocket, 🚀 Make fuel | the rocket |
| 🧹 Clean panels | a sun panel |
| 😴 Rest, 🔬 Research | your astronaut |
| 🧭 Explore | a glowing marker on the map |

### The resource web

```
🌱 Gardens make 🍎 food and 🫁 air
   ↓ but they drink 💧 water and use ⚡ power
⛏️ Water makers give water but use power
   ↓
☀️ Sun panels give power, but 🌪 storms and dust hide the sun
   ↓
🛡️ Walls keep storms out
```

---

## 🏁 How to win

Before Day 21 ends, you need **all** of these:

- 🛠 Rocket fix at **100**
- 🚀 Fuel at **100**
- ⭐ **3 Nav Cores** (found by exploring)
- 🧩 **3 rocket parts**: ⚙️ Engine, 🛡️ Heat Shield, 🔌 Guidance Chip

## ☠ How you lose

- ❤ Health reaches 0.
- Air, Water, Food or Power stays empty for **3 days in a row** (life support fails).
- You have almost no power, no parts, and no way to get more (nothing left to do).
- The rocket is not fully ready by Day 21.

---

## 🔬 Upgrades (Research)

| Upgrade | Cost | Effect |
|---|---|---|
| ☀️ Solar Cells+ | 4 🔧 | Panels make 35% more power |
| ⛏️ Deep Drill | 4 🔧 | Each water maker gives +4 water per day |
| 🚀 Turbo Fuel | 5 🔧 | Make fuel gives +10 more |
| 🧹 Dust Guard | 3 🔧 | Sand never blocks your panels |
| 🏥 Med Bay | 4 🔧 | Rest gives +25 health |

## 🏆 Achievements

| | Achievement | How |
|---|---|---|
| 🚀 | Home at Last | Win the game |
| 😤 | Mars Legend | Win on Hard |
| 🛡️ | Untouchable | Win without losing any health |
| ⭐ | Fast Navigator | Find all 3 Nav Cores by Day 10 |
| 👽 | Beyond the Stars | Find the secret ending |
| 🔬 | Inventor | Unlock all 5 upgrades |
| 🧩 | Mechanic | Collect all 3 rocket parts |

> 🤫 Hint: strange glyphs have been seen at the Ancient Ruins...

---

## 🚀 Run it locally

The whole game is one HTML file.

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

Then open `index.html` in any modern browser (double-click it, or use a local server such as `python3 -m http.server` and visit `http://localhost:8000`).

> An internet connection is needed the first time because [three.js](https://threejs.org/) (r128) loads from the cdnjs CDN.

## 🌐 Deploy with GitHub Pages

1. Push the project to GitHub with the game file named `index.html`.
2. Open your repo → **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose branch **main** and folder **/ (root)**, then click **Save**.
5. Wait a minute. Your game will be live at `https://<your-username>.github.io/<your-repo-name>/`.

---

## 🛠 Built with

- HTML, CSS and vanilla JavaScript (single file)
- [three.js](https://threejs.org/) r128 for the 3D world
- Web Audio API for all sound effects and music
- `localStorage` for settings, achievements and saved games

## 📁 Project structure

```
.
├── index.html   # the entire game
└── README.md    # this file
```

## 👥 Team Ra.One

| | |
|---|---|
| 👨‍🚀 **Aman Singh** | Developer |
| 👩‍🚀 **Isha Mande** | Developer |

## 📸 Screenshots

*Add screenshots here: create a `screenshots/` folder and use `![Gameplay](screenshots/gameplay.png)`.*

## 📄 License

Add a license file (for example MIT) to tell others how they may use this project.

---

© 2026 Team Ra.One · Aman Singh & Isha Mande
