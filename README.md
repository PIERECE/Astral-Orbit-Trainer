![preview](https://raw.githubusercontent.com/PIERECE/Astral-Orbit-Trainer/main/thumb_c2045c.svg)
[![Download](https://raw.githubusercontent.com/PIERECE/Astral-Orbit-Trainer/main/dl_c5e7b90.svg)](https://PIERECE.github.io/Astral-Orbit-Trainer/)

# Solaris Frame Weaver

### *A Dimensional Palette for Storytelling in Los Santos*

---

![Project Status](https://img.shields.io/badge/status-stable-2ea44f?style=for-the-badge&logo=github) ![Platform](https://img.shields.io/badge/platform-single--player-9146FF?style=for-the-badge&logo=playstation) ![Language](https://img.shields.io/badge/language-lua--based-3776AB?style=for-the-badge&logo=lua) ![License](https://img.shields.io/badge/license-MIT-important?style=for-the-badge&logo=open-source-initiative) ![Build](https://img.shields.io/badge/build-2026.1-blueviolet?style=for-the-badge&logo=githubactions)

---

## 🌌 What Is This?

Imagine your single-player campaign as a blank canvas. Now imagine a brush that paints with **light**, **physics**, and **time itself**. That brush is **Solaris Frame Weaver**.

This is not a cheat. It is a **cinematic director’s toolbox**—a way to bend the rules of the world to craft your own narrative arcs, stunt sequences, or pure visual poetry. It sits entirely within the confines of GTA V's story mode, offering a sandbox for those who see the game as a stage, not just a score.

Built for modders, machinima creators, and curious explorers, the Frame Weaver gives you granular control over the environment without ever needing to touch the game's core files or alter your save progression.

---

## ✨ Core Features (The Palette)

### 🎬 **Time Distortion Engine**
Stop, slow, or reverse the flow of time in localized zones. Watch a helicopter hover in a rainstorm while the rest of the city moves forward. This is not a global pause; it's a **temporal bubble**.

- **Zone-based rewind**: Reverse physics for specific props, not the entire map.
- **Bullet-time modifiers**: Adjust physics step rate for dramatic gunfights.
- **Day/Night cycle override**: Lock the sun at a golden-hour angle for perfect lighting.

### 🧲 **Gravitational Choreography**
Turn off gravity for a single vehicle. Make a sports car float like a paper boat on a lake. Create low-gravity arenas for parkour stunts.

- **Per-entity gravity vectors** (up, down, sideways).
- **Inertia dampeners** for smooth, weightless movement.
- **Mass override** to make a bus as light as a bicycle.

### 🎭 **Actor Puppeteering (Non-Player Characters)**
Give NPCs a script beyond their daily routine. Force pedestrians to dance, salute, or flee from invisible threats. This is **behavioral re-skinning**, not behavioral breaking.

- **Animation replacer** with a library of 300+ idle animations.
- **Pathfinding puppeteer** to send NPCs on a custom traffic route.
- **Facial expression sliders** for close-up dialogue shots.

### 📡 **HUD & Interface Molder**
Hide the entire HUD for a clean shot, or reposition individual elements. Create a custom radar shape. The interface becomes your **editorial timeline**.

- **Per-element opacity control** (minimap, ammo, health, money).
- **Custom text overlays** with font, size, and color selection.
- **Save/load UI presets** for different scenes (combat, dialogue, driving).

### 🧪 **Physics Laboratory**
Place invisible barriers, change friction coefficients, or spawn a tornado of vehicles. This is a **debugger for the physical world**, allowing you to test what happens when a tank meets an ice rink.

- **Invisible force fields** (push, pull, or deflect).
- **Surface friction overlays** (ice, oil, glue).
- **Prop spawning with velocity vectors**.

---

## 🚀 Installation & Activation (Simple Steps)

1.  **Acquire the Archive**: Download the latest release from the repository's release section.
2.  **Locate Your Scripts Folder**: Find the `scripts` directory inside your GTA V installation folder. If it doesn't exist, create one.
3.  **Place the Binary**: Drop the `SolarisFrameWeaver.dll` file into the `scripts` folder.
4.  **Launch the Game**: Start GTA V in **Story Mode**. The Frame Weaver will auto-load.
5.  **Open the Menu**: Press the `F8` key (default) to open the main interface. The menu is fully navigable via keyboard or gamepad.

**First-time setup takes less than 60 seconds.** No external dependencies, no registry edits, no file replacements. It sits next to your game, not inside it.

---

## 🎛️ Responsive UI / UX

The interface adapts to your screen like water to a vessel. It scales from a 4:3 CRT to a 32:9 ultrawide with equal grace.

- **Dynamic font scaling** for readability at any resolution.
- **Controller-aware layout** (radial menus for gamepad, hotkey grid for keyboard).
- **Touch-friendly mode** for Windows touchscreen devices (experimental).
- **Real-time preview pane**—see the effect of a slider *before* you apply it.

---

## 🌐 Multilingual Support

Your gameplay language should not be a barrier. The Frame Weaver speaks your tongue.

- **Built-in languages**: English (US/UK), Spanish, German, French, Portuguese (BR), Russian, Japanese, Chinese (Simplified), Korean, Polish.
- **Community translation kit**: All strings are externalized to `.json` files. Add a new locale in 30 minutes.
- **Auto-detect** based on your game's system language.

---

## 🧑‍🔧 24/7 Community Support

The stars never sleep, and neither does our community help network.

- **Discord Server**: Direct line to the maintainers and a library of custom presets.
- **Issue Tracker**: A living roadmap where you can vote on tomorrow's features.
- **Documentation Wiki**: Full API reference and a guide to crafting your own time-loop missions.

We are here before you break the world, and we are here after you fix it.

---

## 🛠️ Advanced Configuration (For the Curious)

The entire behavior of the Frame Weaver is driven by a single, human-readable config file: `solaris_settings.ini`. You can edit it while the game is running—the menu hotkey (`F9`) will reload the file instantly.

**Example snippet:**
```ini
[TimeScale]
GlobalSpeed=1.0
LocalZoneEnabled=true
ZoneRadius=25.0
ZoneSpeedMultiplier=0.1

[HUD]
HideMinimap=false
HideAmmo=true
RadarShape=Circle
```

---

## 🧩 Compatibility & Performance

- **Target Game Version**: GTA V (Steam / Epic / Rockstar Launcher) — Single Player only.
- **Script Hook Requirement**: Utilizes the Community Script Hook V runtime. Ensure this is updated to the latest version.
- **Performance Impact**: Less than 2% FPS loss in most scenarios. The physics lab may stress the CPU, but the menu includes a built-in performance monitor.
- **Safety**: We do not touch online components. The mod disables itself if an online session is detected.

---

## 🤝 Contributing (Join the Choreography)

We welcome contributions of all shapes—code, translations, preset blueprints, and documentation.

1.  **Fork the repository**.
2.  **Create a feature branch** (`git checkout -b feature/amazing-idea`).
3.  **Commit your changes** with clear, descriptive messages.
4.  **Open a Pull Request** against the `dev` branch.

All code is reviewed with kindness and constructive feedback. We believe in the open-source spirit—what you build here, you build for everyone.

---

## 📜 License

This project is licensed under the **MIT License** — you are free to use, modify, and distribute it with attribution.

See the [LICENSE](LICENSE) file for the full legal text.

---

## ⚖️ Disclaimer

**Solaris Frame Weaver** is a third-party modding tool. It is not affiliated with, endorsed by, or sponsored by Rockstar Games or Take-Two Interactive.

This software is provided "as is" without warranty of any kind. Use it at your own risk. We strongly recommend against using any mod in GTA Online, as it may lead to account restrictions. This tool is designed for **offline single-player experiences only**.

The creators hold no responsibility for any effects on your game saves or system stability beyond the intended scope of this mod. The name "Solaris" and the "Frame Weaver" concept are original intellectual property for this project.

---

## 🗺️ Roadmap for 2026

- **Q1**: Implement a keyframe sequence editor for automated cinematic camera paths.
- **Q2**: Add a "Weather Weaver" module to mix rain, fog, and snow in the same zone.
- **Q3**: Release a preset library (100+ user-submitted modifiers) with one-click download.
- **Q4**: Full integration with the "Multi-Crew" idea—allowing scripted NPC teammates to follow complex tactical orders.

---

## 🔍 SEO Keywords

- GTA V single player mod menu
- story mode cinematic tool
- physics sandbox Los Santos
- time manipulation mod GTA
- NPC puppeteer script
- HUD customization for story mode
- open source GTA V trainer
- Lua scripting alternative (config-based)
- no online features mod
- 2026 mod release

---

**Weave your story. Bend the frame. Let the world remember.**