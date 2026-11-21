<div align="center">

<a href="https://gearcadengine.web.app">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset=".github/assets/banner-light.png">
    <img alt="GearCAD" src=".github/assets/banner-light.png" width="460">
  </picture>
</a>

### A VEX IQ CAD you can test.

Build robots from the official VEX IQ parts, check how the mechanism moves,<br>
and run it in a physics simulation, all in your browser.

[![Open GearCAD](https://img.shields.io/badge/Open_GearCAD-gearcadengine.web.app-0167FC?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://gearcadengine.web.app)

[![Latest release](https://img.shields.io/github/v/release/GearCAD-App/gearcad-engine?include_prereleases&sort=semver&label=release&color=32D1FC)](https://github.com/GearCAD-App/gearcad-engine/releases)
[![SemVer](https://img.shields.io/badge/versioning-SemVer-0167FC)](https://semver.org)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?logo=threedotjs&logoColor=white)
![WebGPU](https://img.shields.io/badge/WebGPU-005A9C?logo=webgpu&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase_Hosting-DD2C00?logo=firebase&logoColor=white)

[**Open the app**](https://gearcadengine.web.app) ·
[**Releases**](https://github.com/GearCAD-App/gearcad-engine/releases) ·
[**Report a bug**](https://github.com/GearCAD-App/gearcad-engine/issues/new/choose)
<!-- Add when ready:  · [**Docs**](https://<docs>.pages.dev) · [**Discord**](https://discord.gg/<invite>) -->

</div>

---

## What is GearCAD?

GearCAD is a free, browser-based CAD for **VEX IQ** robots. There's nothing to
install and no account to make: open [gearcadengine.web.app](https://gearcadengine.web.app)
and start building.

It's made for teams who want to know a design works **before** they build it:
GearCAD understands gears, hinges and motors, so you can see what turns, how
fast, and with how much torque, then press **Simulate** and drive it.

## Features

| | |
| --- | --- |
| 🧩 **The real parts** | 480+ official VEX IQ parts, converted from VEX's own CAD files, in the official colours. |
| 🧲 **Snapping** | Parts snap to holes, pins and shafts; gears snap into mesh, and jammed gears get fixed automatically. |
| ⚙️ **Mechanism** | See bodies, hinges and gear trains, with the speed and torque of every gear. |
| 🕹️ **Simulate** | Run your robot in a physics simulation with VEX IQ motors. |
| 📏 **Competition sizes** | Shows the starting size limit for VIQRC (R3) and RECF Engage (2.2.1). |
| 🕓 **Never lose work** | Every change saves by itself. Version history keeps autosave points and named versions you can look at in 3D and restore. |
| 📁 **Your files** | Each CAD lives in a `.gearcad` file you choose (Chrome and Edge). Keep it in Google Drive or OneDrive to use it on any computer. |
| 📸 **Render** | Studio-quality, path-traced pictures of your robot, up to 4K, with a transparent background if you like. |
| 🔁 **Open formats** | Export LDraw (`.ldr`) to use your model in other programs. |

## Getting started

1. Go to **[gearcadengine.web.app](https://gearcadengine.web.app)**.
2. Click **New CAD**, give it a name and pick a workspace (Mechanism, Robot or IQ Field).
3. Drag parts in from the Parts list. **Help → Keyboard and mouse** lists every shortcut.

**Browsers:** GearCAD works best in **Chrome** or **Edge** (saving to files and
Render need them). Firefox and Safari work too, and keep CADs in the browser
with Download.

## Releases and versions

GearCAD uses [Semantic Versioning](https://semver.org): `MAJOR.MINOR.PATCH`.

| Change | Example |
| --- | --- |
| Bug fix | `0.1.0` → `0.1.1` |
| New feature | `0.1.1` → `0.2.0` |
| Something that breaks old files or removes a feature | `1.3.0` → `2.0.0` |

Builds before a version is finished are marked **alpha**, **beta** or **rc**
(`0.1.0-alpha`, `0.1.0-beta.2`). Every version that goes live on
gearcadengine.web.app has a [release](https://github.com/GearCAD-App/gearcad-engine/releases)
here with what changed. The version you're using is in **Help → About**.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/GearCAD-App/gearcad-engine/issues/new/choose).
Please include your GearCAD version (Help → About) and browser.

## Credits

VEX IQ part models © VEX Robotics, Inc., converted from VEX's official CAD
files and used for education. VEX and VEX IQ are trademarks of Innovation
First, Inc.

GearCAD is an independent, free project: it isn't affiliated with or endorsed
by VEX Robotics or the REC Foundation.

## License

GearCAD is free to use, but it is **not open source**. The app's source code
is private. This repository holds GearCAD's releases, documentation and issue
tracker. See [LICENSE](LICENSE).

<div align="center">
<br>
<img src=".github/assets/mark.png" width="40" alt="">
<br>
<sub>Made for VEX IQ teams.</sub>
</div>
