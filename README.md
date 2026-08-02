# 🛸 DroneHunter-5.8

![Unreal Engine 5.8](https://img.shields.io/badge/Engine-Unreal_Engine_5.8-blue?logo=unrealengine)
![Language](https://img.shields.io/badge/Language-C%2B%2B%20%2F%20Blueprints-informational)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?logo=windows)

**DroneHunter-5.8** is an action-packed Unreal Engine 5.8 game project where players engage in high-octane combat against autonomous hostile drone swarms in dynamic 3D environments. Built with performance and modularity in mind, this project showcases advanced flight mechanics, dynamic AI targeting, custom weapon systems, and high-fidelity visual effects.

---


## 🌟 Key Features

- **Dynamic Drone AI:** State-machine and Behavior Tree-driven autonomous flight patterns, player tracking, and aggressive swarm attack runs.
- **Advanced Targeting System:** Lock-on HUD mechanics, lead-indicator reticles, and real-time distance tracking.
- **Modular Arsenal:** Customizable weaponry (ballistic, plasma, and lock-on missile launchers) built on expandable base classes.
- **Destructible Drone Components:** Detailed hit-reaction physics and procedural explosion effects on neutralizations.
- **Optimized Performance:** Leveraging Unreal Engine 5.8 Nanite and Lumen systems for realistic environment rendering and lighting.

---

## 🛠️ Tech Stack & Requirements

- **Engine Version:** Unreal Engine 5.8 or higher
- **IDE:** Visual Studio 2022 (with *Desktop Development with C++* and *Game Development with C++* workloads)
- **OS:** Windows 10/11 (64-bit)
- **Graphics API:** DirectX 12 recommended

---

## 🚀 Getting Started

### Prerequisites

Ensure you have Unreal Engine 5.8 installed via the [Epic Games Launcher](https://store.epicgames.com/).

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ChiraagRokade/DroneHunter-5.8.git
   ```

2. **Generate Project Files:**
   - Right-click `DroneHunter.uproject` in the root folder.
   - Select **Generate Visual Studio project files**.

3. **Build the Project:**
   - Open the resulting `.sln` file in Visual Studio 2022.
   - Set the build configuration to `Development Editor` and target `Win64`.
   - Build the solution (`Ctrl + Shift + B`).

4. **Launch:**
   - Double-click `DroneHunter.uproject` to launch the Unreal Editor.

---

## 🎮 Controls

| Action | Key / Input |
| :--- | :--- |
| **Move / Strafe** | `W`, `A`, `S`, `D` |
| **Look / Aim** | `Mouse` |
| **Fire Weapon** | `Left Mouse Button` |
| **Aim Down Sights (ADS)** | `Right Mouse Button` |
| **Lock-On Target** | `Middle Mouse Button` / `F` |
| **Reload** | `R` |
| **Sprint / Dash** | `Left Shift` |

---

## 📁 Repository Structure

```text
DroneHunter-5.8/
├── Config/                  # Project configuration files
├── Content/                 # Game assets (Blueprints, UI, Materials, Audio, Meshes)
│   ├── Core/                # GameMode, GameInstance, PlayerController
│   ├── Characters/          # Player Character setup and animations
│   ├── Drones/              # Enemy Drone meshes, Blueprints, AI Controllers
│   ├── Weapons/             # Weapon base classes, projectiles, VFX
│   └── UI/                  # HUD, crosshairs, menu system
├── Source/                  # C++ source code files
│   ├── DroneHunter/         # Main module header/cpp files
│   └── Public/ & Private/   # C++ Classes (AI, Weapons, Mechanics)
└── DroneHunter.uproject     # Main project file
```

---

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add New Feature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request