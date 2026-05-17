# Hollow Knight - Standalone DebugMod (v1.5.12620)

A fully converted, standalone version of the legendary **DebugMod** rewritten specifically for Hollow Knight version **1.5.12620** (Latest Steam Update). This port completely bypasses the traditional Modding API (Lumafly) and runs directly as a native **BepInEx 5** plugin.

## 🚀 Key Features
* **API-Independent:** Runs completely standalone. No need to install Lumafly or the standard Modding API, minimizing overhead and preventing version mismatch crashes.
* **1.5.12620 Native Compatibility:** Fixed the infamous MonoMod Preloader/Harmony crashes (`MissingMethodException`) caused by Team Cherry's native D3D12/Unity engine updates.
* **Optimized Core:** Synchronized with the latest 2026 MonoMod/Cecil dependencies for flawless injection.

---

## ⚠️ Important Project Status & Notes

> 📌 **DEVELOPMENT NOTE (Current Status: 99% Complete)**
> The project has successfully achieved native code injection and core functionality. However, it is currently in the final polishing phase:
> * **Menu Hotkey:** The current default key to toggle the Debug Menu is **F1**.
> * **KeyCode Notice:** A few minor input KeyCodes are currently bugged or mismatched due to the new Unity Input System changes in v1.5.12620. A hotfix to re-map these remaining keybindings is actively being worked on and will be pushed in the next update! Everything else is fully functional.

---

## 🛠️ Installation Guide

Since this is a Standalone BepInEx plugin, installation is straightforward:

1. Make sure you have **BepInEx 5** (latest 2026 build compatible with Unity 2022+) correctly installed in your Hollow Knight directory.
2. Go to the [Releases](https://github.com/your-username/HollowKnight-Standalone-DebugMod/releases) section of this repository and download `DebugMod.dll`.
3. Move the downloaded `DebugMod.dll` into your game's plugin folder:
   ```text
   Hollow Knight/BepInEx/plugins/
