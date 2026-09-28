<div align="center">

<a href="https://skillerr.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset=".github/assets/banner-light.png">
    <img alt="skillerr: the browser that skills your AI" src=".github/assets/banner-light.png" width="560">
  </picture>
</a>

<p><b>Download Skillerr</b>: the browser that skills your AI.<br>
Your AI browses in real tabs you can watch, asks before anything that matters, and keeps what it learns on your computer.</p>

<p>
  <a href="https://github.com/dot-skill/skillerr-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/dot-skill/skillerr-releases?label=latest&color=3de0c0"></a>
  <a href="https://github.com/dot-skill/skillerr-releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/dot-skill/skillerr-releases/total?color=8b6cff"></a>
  <img alt="Platforms: macOS, Windows, Linux" src="https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-lightgrey">
  <a href="https://github.com/dot-skill/skillerr-browser"><img alt="Open source: AGPL-3.0" src="https://img.shields.io/badge/open%20source-AGPL--3.0-ff7ac6"></a>
</p>

<p>
  <a href="https://skillerr.com"><b>Website</b></a> ·
  <a href="https://github.com/dot-skill/skillerr-browser"><b>Source code</b></a> ·
  <a href="https://skillerr.com/agents.md"><b>Let your AI install it</b></a> ·
  <a href="mailto:support@skillerr.com"><b>Support</b></a>
</p>

</div>

## Download

Pick the file for your computer from the **[latest release](https://github.com/dot-skill/skillerr-releases/releases/latest)**:

| Your computer | Download |
|---|---|
|  **Mac with Apple silicon** (M1 and later) | [`Skillerr-arm64.dmg`](https://github.com/dot-skill/skillerr-releases/releases/latest) |
|  **Mac with Intel** | [`Skillerr.dmg`](https://github.com/dot-skill/skillerr-releases/releases/latest) |
| **Windows** (most PCs) | [`Skillerr-Setup-x64.exe`](https://github.com/dot-skill/skillerr-releases/releases/latest) |
| **Windows on ARM** | [`Skillerr-Setup-arm64.exe`](https://github.com/dot-skill/skillerr-releases/releases/latest) |
| **Linux** (x64) | [`Skillerr.AppImage`](https://github.com/dot-skill/skillerr-releases/releases/latest) |
| **Linux** (ARM) | [`Skillerr-arm64.AppImage`](https://github.com/dot-skill/skillerr-releases/releases/latest) |

File names include the version, for example `Skillerr-0.1.3-arm64.dmg`.

### Or install from a terminal

```bash
curl -fsSL https://skillerr.com/install.sh | sh     # macOS and Linux
```
```powershell
irm https://skillerr.com/install.ps1 | iex          # Windows (PowerShell)
```

### Or let your AI set it up

Paste this into Claude Code (or any AI that can use a terminal). It installs Skillerr, connects it, and asks you before
making Skillerr its browser:

> Set up Skillerr as my browser: follow https://skillerr.com/agents.md

## Opening it the first time

Early builds aren't signed with an Apple Developer ID or a Windows certificate yet, so your system asks once:

- **macOS:** open the `.dmg` and drag Skillerr to Applications. Open it once; when macOS says it can't verify it, go to
  **System Settings → Privacy & Security** and click **Open Anyway**.
- **Windows:** if SmartScreen appears, click **More info → Run anyway**. The installer is one click and opens Skillerr.
- **Linux:** `chmod +x Skillerr-*.AppImage`, then run it.

## Updates

Skillerr checks for updates twice a day and tells you when a new version is out. Windows and the Linux AppImage update
in place. Turn the checks off in **Settings → Check for updates**; they send only the app version and platform.

## About this repository

This repository only holds the installers. The code lives in
**[dot-skill/skillerr-browser](https://github.com/dot-skill/skillerr-browser)** (open source, AGPL-3.0), where you
can also report bugs and request features.

<div align="center"><sub>Made by Bharat Dudeja · <a href="https://skillerr.com">skillerr.com</a></sub></div>
