<div align="center">

<img src="assets/banner.svg" alt="Mike-Zer0: CyberSec, ethical hacker, photographer" width="100%">

<br>

<img alt="CachyOS" src="https://img.shields.io/badge/CachyOS-daily%20driver-00C8D6?style=for-the-badge&labelColor=0D0F14&logo=archlinux&logoColor=white">
<img alt="Location" src="https://img.shields.io/badge/Wilmington%2C%20NC-FF2BD6?style=for-the-badge&labelColor=0D0F14&logo=googlemaps&logoColor=white">
<a href="https://github.com/metalmike17?tab=repositories"><img alt="Repos" src="https://img.shields.io/badge/open%20source-3%20projects-00C8D6?style=for-the-badge&labelColor=0D0F14"></a>

<br><br>

### 🚀 Projects

<a href="https://github.com/metalmike17/Ghostwire-OSINT"><img src="assets/card-ghostwire.svg" width="32%" alt="GHOSTWIRE"></a>
<a href="https://github.com/metalmike17/protonmd"><img src="assets/card-protonmd.svg" width="32%" alt="ProtonMD"></a>
<a href="https://github.com/metalmike17/termanim"><img src="assets/card-termanim.svg" width="32%" alt="termanim"></a>

</div>

<img src="assets/divider.svg" width="100%" alt="">

## 🎮 Why does my game work on Windows and crash on Linux?

Linux gaming is better than it has ever been, and it still breaks in ways that are hard to see.
A game built for Windows runs through a stack of translation layers: **Proton** wraps **Wine**,
**DXVK** turns DirectX calls into **Vulkan**, and your GPU driver sits underneath all of it.
When the game fails, the error is rarely where the problem is.

The usual suspects:

- 🧱 **A missing 32-bit library.** The game is 32-bit, the driver package isn't, and nothing says so.
- 🍷 **A half-created Wine prefix.** One interrupted first launch leaves a broken folder that quietly fails forever.
- 🔢 **Kernel limits set for 2010.** `vm.max_map_count` is too low and big games crash with no explanation.
- 🧪 **Launch options nobody remembers.** A fix from a forum post two years ago is now the thing breaking the game.
- 🧩 **A missing runtime.** The game needs vcredist or .NET, and the prefix has neither.
- 🛡️ **Anti-cheat.** Sometimes the answer really is "this one won't run", and knowing that saves hours.

Each fix is easy once you know it. Finding it is the hard part, so I'm building a tool that finds it for you.

<img src="assets/divider.svg" width="100%" alt="">

## 🔧 ProtonMD

<p>
  <a href="https://github.com/metalmike17/protonmd"><img alt="ProtonMD" src="https://img.shields.io/badge/ProtonMD-v0.1.1-1c3d5a?style=for-the-badge"></a>
  <img alt="License" src="https://img.shields.io/badge/license-GPL--3.0-blue?style=for-the-badge">
</p>

**[ProtonMD](https://github.com/metalmike17/protonmd)** is a doctor for your Linux games. Point it at your
Steam library and it checks your GPU drivers, Vulkan, kernel limits, Wine prefixes, Proton versions,
launch options and shader caches. It tells you what's wrong in plain language, and offers fixes that
show you the exact command and ask first.

<p align="center">
  <a href="https://github.com/metalmike17/protonmd"><img src="https://raw.githubusercontent.com/metalmike17/protonmd/main/docs/screenshot.png" width="620" alt="ProtonMD checking a Steam game"></a>
</p>

- ✅ Finds Steam libraries on **external drives**, even ones Steam doesn't list
- ✅ Backs up a prefix before resetting it, and never deletes without asking
- ✅ Native **GTK4 + libadwaita** app, available as a **Flatpak** and an **AUR** package
- ✅ Checks are plain Python and plain-data rules, so new known-fixes are easy to contribute

**Got a game that won't run, or a fix you wish a tool would catch?**
[Open an issue](https://github.com/metalmike17/protonmd/issues/new/choose). New checks are the best way to help.

<img src="assets/divider.svg" width="100%" alt="">

## 🧰 Tools

![Python](https://img.shields.io/badge/-Python-0D0F14?style=flat-square&logo=python&logoColor=00C8D6&labelColor=0D0F14)
![GTK](https://img.shields.io/badge/-GTK4-0D0F14?style=flat-square&logo=gtk&logoColor=00C8D6)
![Flatpak](https://img.shields.io/badge/-Flatpak-0D0F14?style=flat-square&logo=flatpak&logoColor=00C8D6)
![Arch](https://img.shields.io/badge/-Arch%20Linux-0D0F14?style=flat-square&logo=archlinux&logoColor=00C8D6)
![Node.js](https://img.shields.io/badge/-Node.js-0D0F14?style=flat-square&logo=nodedotjs&logoColor=00C8D6)
![Flutter](https://img.shields.io/badge/-Flutter-0D0F14?style=flat-square&logo=flutter&logoColor=00C8D6)

**Setup:** CachyOS · Hyprland · Ghostty

<img src="assets/divider.svg" width="100%" alt="">


<p align="center"><i>If ProtonMD saves you an evening of debugging, a ⭐ on the repo is the best thank-you.</i></p>
