# 🛸 SpaceTug Orbital Simulator (STOS) — Trial Edition v1.0.1

Author: **Yuvaraj Singh**  
Copyright (c) 2026 **SPACETUG Private Limited**

[![Release](https://img.shields.io/github/v/release/yuvakali/stos-trial-releases?style=for-the-badge&color=00f2fe)](https://github.com/yuvakali/stos-trial-releases/releases/tag/v1.0.1)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-00d2ff?style=for-the-badge)](https://github.com/yuvakali/stos-trial-releases/releases/tag/v1.0.1)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)](#license)
[![Physics](https://img.shields.io/badge/Physics-GMAT--Grade%206--DOF-green?style=for-the-badge)](#architecture)

> **Real-time 6-DOF Orbital Robotics, Rendezvous & Proximity Operations (RPO), Satellite Servicing, and Autonomous Guidance, Navigation & Control (GNC) Simulation Platform.**

---

## ⚡ Quick Download Links (v1.0.1)

Standalone desktop installers — **100% offline**, zero prerequisites required.

| Platform | Package | Download Link | Installation Command / Instructions |
|---|---|---|---|
| **Ubuntu / Debian** | `.deb` package | [**Download `.deb`**](https://github.com/yuvakali/stos-trial-releases/releases/download/v1.0.1/stos-trial_1.0.1_amd64.deb) | `sudo apt install ./stos-trial_1.0.1_amd64.deb` |
| **Linux (Universal)** | `.AppImage` | [**Download `.AppImage`**](https://github.com/yuvakali/stos-trial-releases/releases/download/v1.0.1/STOS-Trial-1.0.1-x86_64.AppImage) | `chmod +x STOS-Trial-1.0.1-x86_64.AppImage && ./STOS-Trial-1.0.1-x86_64.AppImage` |
| **Windows** | Setup Installer | [**Download `.exe`**](https://github.com/yuvakali/stos-trial-releases/releases/download/v1.0.1/STOS-Trial-Setup-1.0.1.exe) | Run `STOS-Trial-Setup-1.0.1.exe` wizard |
| **Windows** | Portable Executable | [**Download Portable**](https://github.com/yuvakali/stos-trial-releases/releases/download/v1.0.1/STOS-Trial-1.0.1-Portable.exe) | Double-click `STOS-Trial-1.0.1-Portable.exe` (no install) |
| **macOS (Apple Silicon)** | `.dmg` Image | [**Download `.dmg`**](https://github.com/yuvakali/stos-trial-releases/releases/download/v1.0.1/STOS-Trial-1.0.1-arm64.dmg) | Mount `.dmg` and drag **STOS Trial** to `/Applications` |

---

## 🌟 Key Simulation Modules

### 1. 🌌 Orbital Transfer Engine & Strategy Planner
- **Impulsive & Low-Thrust Transfers**: Hohmann, Bi-elliptic, Generalized 3D Hohmann, Lambert targeting, Sims-Flanagan transcription.
- **Perturbation-Leveraged Maneuvers**: J2 nodal precession drift matching, Edelbaum low-thrust spiral, differential drag phasing.
- **Constraint Engine**: Real-time evaluation of Δv budget, time-of-flight bounds, maximum G-force limits, thermal illumination constraints, and power availability.

### 2. 🎯 Rendezvous & Proximity Operations (RPO)
- **Clohessy-Wiltshire (CW) / Hill Equations**: Relative motion propagation in Local-Vertical Local-Horizontal (LVLH) frame.
- **Constrained Corridor Trajectories**: V-bar, R-bar, Natural Motion Circumnavigation (NMC), Teardrop approach, and Auto-CAS collision avoidance corridors.
- **Sensor Suite Audit**: Real-time evaluation of LiDAR rangefinder, Star Tracker, Thermal IR, and Optical Navigation sensor readiness.

### 3. 🔬 Autonomous Inspection & Robotic Capture AI
- **Multi-Spectral Sensor Fusion**: Synthetic thermal IR, LiDAR point clouds, RGB, and depth mapping.
- **Structural Integrity Analysis**: Automated density and structural stress mapping of space debris (solar panels, rocket bodies, MLI blankets).
- **AI Gripper Point Selection**: Multi-objective scoring algorithm identifying optimal capture points based on structural load limit, surface temperature, and spin-induced torque.

### 4. 🛰️ Spacecraft Configuration & Global Fuel Tracking
- **3D Interactive Visualizer**: Real-time parametric modification of spacecraft dimensions, solar array span, and thruster nozzle layout.
- **Integrated Mass Properties**: Automatic recalculation of wet/dry mass, center of mass (CoM), moment of inertia tensor, and specific impulse (I_sp).
- **Continuous Fuel Tracking**: Seamless fuel consumption logging across Transfer -> Rendezvous -> Proximity Ops -> Capture phases.

---

## 🛠️ What's New in Release v1.0.1

- **⚡ Instant Proximity Operations**: Auto-equips default sensor suites on click to eliminate manual setup blockers.
- **🛡️ Procedural 3D Mesh Fallback**: 3D debris inspection viewer automatically renders procedural satellite models if external CAD files are missing.
- **💻 Desktop Process Lifecycle**: Clean background process termination on exit to prevent port 5199 conflicts on app restart.
- **🧭 Interactive Tour Guide**: Restartable product tour guide accessible anytime from any screen.
- **🔥 HUD Telemetry Cleanup**: Active burn simulation progress bars and floating panels auto-dismiss cleanly during page navigation.

---

## 💻 Installation Notes & Platform Guidance

### 🐧 Ubuntu / Debian
```bash
# Install via APT
sudo apt install ./stos-trial_1.0.1_amd64.deb

# Launch application
stos-trial
```

### 🐧 Universal Linux AppImage
```bash
chmod +x STOS-Trial-1.0.1-x86_64.AppImage
./STOS-Trial-1.0.1-x86_64.AppImage
```

### 🪟 Windows
1. Double click `STOS-Trial-Setup-1.0.1.exe`.
2. If Windows Defender SmartScreen pops up (*Unrecognized app*), click **More info** -> **Run anyway**.

### 🍎 macOS
1. Double click `STOS-Trial-1.0.1-arm64.dmg` and drag **STOS Trial** to **Applications**.
2. If macOS Gatekeeper blocks opening (*Unidentified developer*), Right-Click **STOS Trial** in Finder -> select **Open** -> click **Open**.

---

## 📄 License & Copyright

Copyright (c) 2026 **SPACETUG Private Limited**. All rights reserved.  
The STOS Trial edition is provided for evaluation purposes. Commercial redistribution without prior authorization is strictly prohibited.
