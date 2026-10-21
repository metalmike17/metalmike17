<h1 align="center">Mike-Zer0</h1>
<p align="center">
  🛡️ CyberSec grad &amp; ethical hacker &nbsp;·&nbsp; 📸 Photographer &nbsp;·&nbsp; 🐧 CachyOS daily driver
</p>

---

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

## 🧰 Tools

![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![GTK](https://img.shields.io/badge/-GTK4-4A86CF?logo=gtk&logoColor=white)
![Flatpak](https://img.shields.io/badge/-Flatpak-4A90D9?logo=flatpak&logoColor=white)
![Arch](https://img.shields.io/badge/-Arch%20Linux-1793D1?logo=archlinux&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=nodedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?logo=flutter&logoColor=white)

**Setup:** CachyOS · Hyprland · Ghostty

<p align="center"><i>If ProtonMD saves you an evening of debugging, a ⭐ on the repo is the best thank-you.</i></p>
