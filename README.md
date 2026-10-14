<p align="center">
  <img src="https://raw.githubusercontent.com/Jeboseeer/CS2-2026-Suite/main/assets/banner.png" width="100%">
</p>

<h1 align="center">CS2 Suite 2026</h1>

<p align="center">
  <b>Advanced external toolkit for Counter-Strike 2. Visual assistance, precision aim, recoil compensation, and full customization — all from a lightweight external overlay.</b>
</p>

<p align="center">
  <a href="https://github.com/Jeboseeer/CS2-2026-Suite"><img src="https://img.shields.io/github/v/release/Jeboseeer/CS2-2026-Suite?style=flat-square&label=Version&color=red"></a>
  <a href="https://github.com/Jeboseeer/CS2-2026-Suite"><img src="https://img.shields.io/github/downloads/Jeboseeer/CS2-2026-Suite/total?style=flat-square&label=Downloads&color=success"></a>
  <a href="https://github.com/Jeboseeer/CS2-2026-Suite"><img src="https://img.shields.io/github/stars/Jeboseeer/CS2-2026-Suite?style=flat-square&label=Stars&color=yellow"></a>
  <a href="https://github.com/Jeboseeer/CS2-2026-Suite"><img src="https://img.shields.io/github/issues/Jeboseeer/CS2-2026-Suite?style=flat-square&label=Issues&color=blue"></a>
  <a href="https://github.com/Jeboseeer/CS2-2026-Suite"><img src="https://img.shields.io/github/license/Jeboseeer/CS2-2026-Suite?style=flat-square&label=License&color=lightgrey"></a>
  <br>
  <img src="https://img.shields.io/badge/Status-Undetected-brightgreen?style=flat-square">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Type-External-orange?style=flat-square">
  <img src="https://img.shields.io/badge/Updated-October%202026-informational?style=flat-square">
</p>

---

## ✨ Features

| Feature | Description |
|---|---|
| 👁️ **Visual Assistance** | Player outlines, distance markers, health bar, name tag |
| 🎯 **Precision Aim** | Smooth aim with adjustable FOV, smoothing, bone priority |
| 🔫 **Recoil Compensation** | Per-weapon recoil control profiles |
| 📡 **Radar Overlay** | Full map overview with live positions |
| 💣 **Grenade Helper** | Trajectory preview for smokes, flashes, molotovs |
| 🎛️ **Config System** | Save and load profiles per weapon and role |
| 🖥️ **External Design** | Runs outside game process — no injection, no hooks |
| 🎨 **Clean UI** | Dark theme, minimal footprint, hotkey-friendly |

---

## 🛡️ Status

| Platform | Status |
|---|---|
| Valve Matchmaking | ✅ Working |
| Premier Mode | ✅ Working |
| Faceit | ⚠️ Use with care |
| Last tested | October 14, 2026 |

---

## 🔧 Technical Details

| Detail | Value |
|---|---|
| Type | External overlay |
| Platform | Windows 10/11 x64 |
| Framework | .NET 8 |
| File Size | 12.4 MB |
| RAM Usage | < 45 MB |
| Rendering | DirectX 11 |
| Input | Hotkey-driven, no writes |

---

## 📥 Installation

```bash
# Download latest release
https://github.com/Jeboseeer/CS2-2026-Suite/releases/latest

# Extract
Right-click CS2_Suite.zip → Extract to Desktop

# Run as Administrator
Right-click CS2Suite.exe → Run as Administrator

# Launch CS2 in borderless window
# Overlay attaches automatically
```

> 💡 **Tip:** Set CS2 to **Borderless Window** mode before running the suite.

---

## 🎮 Presets

| Preset | Best For |
|---|---|
| **Legit** | Low-key settings that look natural |
| **Balanced** | Middle ground between visibility and subtlety |
| **Aggressive** | Maximum information, competitive use |
| **Stream-Safe** | Hides overlay in OBS / Streamlabs |

---

## ⌨️ Hotkeys

| Key | Action |
|---|---|
| `INSERT` | Toggle menu |
| `F1` | Toggle visual assistance |
| `F2` | Toggle aim assist |
| `F3` | Toggle recoil compensation |
| `F4` | Toggle radar |
| `END` | Emergency exit |

---

## 📁 Repository Structure

```
CS2-2026-Suite/
├── assets/
│   ├── banner.png
│   ├── menu.png
│   └── overlay.png
├── src/
│   ├── CS2Suite.csproj
│   ├── Program.cs
│   ├── Overlay.cs
│   ├── VisualsModule.cs
│   ├── AimModule.cs
│   ├── RecoilModule.cs
│   └── RadarModule.cs
├── configs/
│   ├── legit.json
│   ├── balanced.json
│   ├── aggressive.json
│   └── streamsafe.json
├── LICENSE
├── README.md
└── .gitignore
```

---

## ❓ FAQ

<details>
<summary><b>Is it detected?</b></summary>
Currently undetected as of October 2026. External design — no injection, no memory writes. Always check the release notes for the latest status.
</details>

<details>
<summary><b>How does it work?</b></summary>
The suite runs as an external process and renders an overlay on top of the game. It does not modify game files or inject into the game process.
</details>

<details>
<summary><b>Do I need admin rights?</b></summary>
Yes — required for the overlay to attach to the CS2 window.
</details>

<details>
<summary><b>Does it work in fullscreen?</b></summary>
Borderless Window mode is required for the overlay to render.
</details>

<details>
<summary><b>Can I use it on Faceit?</b></summary>
Use at your own discretion. Faceit has its own client-side protections.
</details>

---

## 📊 Project Stats

<p align="center">
  <a href="https://github.com/Jeboseeer/CS2-2026-Suite"><img src="https://img.shields.io/github/stars/Jeboseeer/CS2-2026-Suite?style=social"></a>
  <a href="https://github.com/Jeboseeer/CS2-2026-Suite"><img src="https://img.shields.io/github/forks/Jeboseeer/CS2-2026-Suite?style=social"></a>
  <a href="https://github.com/Jeboseeer/CS2-2026-Suite"><img src="https://img.shields.io/github/watchers/Jeboseeer/CS2-2026-Suite?style=social"></a>
</p>

---

## ⚠️ Disclaimer

This software is provided for **educational and research purposes only**. It demonstrates overlay rendering, input handling, and computer vision techniques. Users are responsible for compliance with the game's terms of service. Not affiliated with Valve.

---

## 🔗 Links

| Resource | URL |
|---|---|
| 📥 Downloads | [Releases Page](https://github.com/Jeboseeer/CS2-2026-Suite/releases) |
| 💬 Discussion | [Discussions](https://github.com/Jeboseeer/CS2-2026-Suite/discussions) |
| 🐛 Bug Reports | [Issues Page](https://github.com/Jeboseeer/CS2-2026-Suite/issues) |

---

<p align="center">
  <sub>CS2 Suite 2026 © 2026 | MIT License | Not affiliated with Valve</sub><br>
  <sub>Maintained by <a href="https://github.com/Jeboseeer">Jeboseeer</a> | Updated: October 2026</sub>
</p>
1
