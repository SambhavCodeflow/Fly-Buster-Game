<div align="center">

<a href="https://play.sambhavgames.workers.dev/fly_buster.html">
  <img src="assets/fly_buster_cover.png" alt="Fly Buster - click to play" width="100%">
</a>

# ✈️ FLY BUSTER 🚓

### Drive. Drift. Fly. Outrun the cops.

A free, open-source **3D neon city driving game** that runs right in your browser.
No download. No login. No build step. Just click and play.

<br>

<a href="https://play.sambhavgames.workers.dev/fly_buster.html"><img src="https://img.shields.io/badge/▶%20PLAY%20NOW-ff2ea6?style=for-the-badge" alt="Play now"></a>
<a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-2ee6c5?style=for-the-badge" alt="MIT License"></a>
<img src="https://img.shields.io/badge/three.js-r128-ffa62e?style=for-the-badge" alt="three.js">
<img src="https://img.shields.io/badge/platform-PC%20%7C%20Mobile-b04dff?style=for-the-badge" alt="PC and Mobile">

<br><br>

[Play](https://play.sambhavgames.workers.dev/fly_buster.html) ·
[Features](#-features) ·
[Controls](#-controls) ·
[Run locally](#-run-it-locally) ·
[Contribute](#-contributing) ·
[Report a bug](../../issues)

</div>

---

## 🎮 About

**Fly Buster** is a single-file WebGL game set in an endless, glowing city. Race through traffic, drift around corners, hit ramps, and switch your Roadster into flight mode to soar over the skyline. Crash into too much traffic and the police will hunt you down. Lose them, grab the orbs, and try to reach **Mars**.

The whole game lives in **one HTML file**, so it is easy to read, fork and remix.

## ✨ Features

| | |
| --- | --- |
| 🏙️ **Endless neon city** | Procedurally generated blocks, parks, ramps, props and glowing orbs |
| 🚗 **3 vehicles** | Supercar (drift king), Roadster (can fly), Robotaxi (tough cruiser) |
| 🛩️ **4 flight modes** | Hover, Jet, Rocket and Hop for the Roadster |
| 🚓 **Cops and heat levels** | Cause trouble and the chase begins. Get caught and you lose points |
| 🔥 **Stunts and score** | Drifts, near misses, roof hops, flips, barrel rolls, big air, gold rings |
| ⏱️ **Checkpoints** | Race the timer and stack bonus points |
| 🔴 **Mars boost** | Collect 5 orbs, fly straight up and reach Mars for a huge bonus |
| 🌅 **Day, sunset, night and rain** | Change the mood of the city any time |
| 👥 **Multiplayer between tabs** | Open the game in more than one tab and the cars share one city |
| 📱 **PC and phone** | Touch controls on mobile, fully remappable keys on desktop |

## 🕹️ Controls

| Action | Key |
| --- | --- |
| Accelerate | `W` |
| Brake / reverse | `S` |
| Steer | `A` `D` or `←` `→` |
| Handbrake drift | `V` |
| Thruster jump (hold) | `Space` |
| Nitro (hold with gas) | `Shift` |
| Take off / land (Roadster) | `F` |
| Change fly mode | `G` |
| Climb / descend | `↑` or `E` / `↓` or `Q` |
| Backflip / Frontflip / Barrel roll (in air) | `Z` / `C` / `X` |
| Day, sunset, night | `T` |
| Rain on / off | `Y` |
| Reset car | `R` |
| Mute engine | `M` |
| Controls panel (remap keys) | `H` |

📱 On touch devices, on-screen buttons appear automatically.

## 💡 Tips

- Hold **Shift + gas** for nitro. Orbs and rings refill it.
- Pass close to traffic at high speed for **near-miss** points.
- Hit the **orange pads** for jumps and the **big white pad** for huge air.
- Fly low between buildings in the Roadster to earn **buzz** points.
- Collect **5 orbs**, then fly straight up to launch toward Mars.

## 🚀 Run it locally

No installation needed.

**Option 1: just open the file**

Double-click `fly_buster.html`, or open `cover.html` for the cover page that launches the game.

**Option 2: tiny local server**

```bash
python -m http.server 8000
# then open http://localhost:8000/fly_buster.html
```

> The game loads [three.js r128](https://threejs.org/) from the cdnjs CDN, so it needs internet the first time. For fully offline play, download `three.min.js` and change the `<script src=...>` line in `fly_buster.html`.

## 📁 Project structure

```
fly-buster/
├── fly_buster.html           # the whole game (HTML + CSS + JS)
├── cover.html                # animated cover page, click to launch
├── assets/
│   └── fly_buster_cover.png  # cover / thumbnail image
├── LICENSE
├── CONTRIBUTING.md
└── README.md
```

## 🧰 Built with

- Plain **HTML, CSS and JavaScript**, no framework, no bundler
- **[three.js](https://threejs.org/)** (WebGL) for 3D graphics
- **BroadcastChannel API** for tab-to-tab multiplayer
- **Web Audio API** for the engine sound

## 🗺️ Roadmap

- [ ] More vehicles and paint colours
- [ ] Missions and police variety
- [ ] Music and sound effects
- [ ] Better performance on low-end phones
- [ ] Online multiplayer (WebSocket / WebRTC)
- [ ] Leaderboard

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md), then:

1. Fork the repo
2. Create a branch: `git checkout -b my-feature`
3. Commit your changes
4. Open a Pull Request

If you like the project, a ⭐ on the repo helps a lot.

## 📄 License

Released under the [MIT License](LICENSE). Free to use, modify and share. Just keep the copyright notice.

## 🙌 Credits

Made with ❤️ by **Sambhav Games**.
3D engine: [three.js](https://github.com/mrdoob/three.js) (MIT).

<div align="center">

**[▶ Play Fly Buster now](https://play.sambhavgames.workers.dev/fly_buster.html)**

</div>
