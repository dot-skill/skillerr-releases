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
|  **Mac with Apple silicon** (M1 and later) | [`Skillerr-mac-arm64.dmg`](https://github.com/dot-skill/skillerr-releases/releases/latest/download/Skillerr-mac-arm64.dmg) |
|  **Mac with Intel** | [`Skillerr-mac-x64.dmg`](https://github.com/dot-skill/skillerr-releases/releases/latest/download/Skillerr-mac-x64.dmg) |
| **Windows** (most PCs) | [`Skillerr-windows-x64.exe`](https://github.com/dot-skill/skillerr-releases/releases/latest/download/Skillerr-windows-x64.exe) |
| **Windows on ARM** | [`Skillerr-windows-arm64.exe`](https://github.com/dot-skill/skillerr-releases/releases/latest/download/Skillerr-windows-arm64.exe) |
| **Linux** (x64) | [`Skillerr-linux-x64.AppImage`](https://github.com/dot-skill/skillerr-releases/releases/latest/download/Skillerr-linux-x64.AppImage) |
| **Linux** (ARM) | [`Skillerr-linux-arm64.AppImage`](https://github.com/dot-skill/skillerr-releases/releases/latest/download/Skillerr-linux-arm64.AppImage) |

Each link is always the newest version. Every release also has the same files with the version in the name
(for example `Skillerr-0.1.8-arm64.dmg`), which is what the in-app updater uses.

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

This repository only holds the installers: there is no code here. Skillerr's source, including its MCP server
([`mcp/`](https://github.com/dot-skill/skillerr-browser/tree/main/mcp)), its tests and its build pipeline, lives in
**[dot-skill/skillerr-browser](https://github.com/dot-skill/skillerr-browser)**. Every installer here is built from
that repository by its GitHub Actions workflow, after the tests pass. Both are open source under
[AGPL-3.0](LICENSE). Report bugs and request features there.

<div align="center"><sub>Made by Bharat Dudeja · <a href="https://skillerr.com">skillerr.com</a></sub></div>
