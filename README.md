# 🎯 CrosshairOverlay

A lightweight, customizable crosshair overlay for Windows built with **C++**, **DirectX9**, and **ImGui**.  
Perfect for training aim, testing recoil patterns, or just having a custom crosshair in any game.

---

## ✨ Features
- Customizable crosshair types:
  - Plus (`+`)
  - Dot (`•`)
  - Circle (`O`)
- Adjustable:
  - Size
  - Color
  - Thickness
  - Outline (toggle + thickness)
  - Offset (X/Y)
- System tray support (runs in background, right-click to exit).
- Config saving/loading.
- Recoil animation profiles for popular FPS games:
  - **Valorant** (Vandal, Phantom)(in developement)
- Portable: no installation required (just run `.exe`).

---

## 📥 Download
Grab the latest **Release build** from the [Releases page](../../releases).

- `CrosshairOverlay.exe` → runs directly (no install needed).  
- Tested on **Windows 10 / 11**.

---

## 🚀 How to Use
1. Download the `.zip` from [Releases](../../releases).
2. Extract it anywhere.
3. Run `CrosshairOverlay.exe`.
4. A crosshair appears centered on your screen.
5. Use the **tray icon** (bottom-right on taskbar) to open/close settings.
6. Customize crosshair style, color, outline, and recoil profiles.

---
## Tray icon

<img width="346" height="156" alt="Screenshot 2025-09-09 210740" src="https://github.com/user-attachments/assets/714d26b5-1c05-41ea-9feb-4083786bc8ee" >

<img width="344" height="152" alt="Screenshot 2025-09-09 211248" src="https://github.com/user-attachments/assets/52caf4c1-9b67-484a-922c-e0af7eac8b53" />


---
## Crosshair
<img width="1919" height="1079" alt="Screenshot 2025-09-09 210659" src="https://github.com/user-attachments/assets/c1179408-f204-477d-b366-d82589eb8813" />

---

<img width="1919" height="1079" alt="Screenshot 2025-09-09 210651" src="https://github.com/user-attachments/assets/33e17233-fe8e-426a-96e0-921152c8c033" />

---
## 🛠 Build Instructions (For Developers)
If you want to build from source:

### Requirements
- Visual Studio 2022 (or newer).
- Windows SDK.
- DirectX 9 SDK (or use `d3d9.lib` from Windows Kits).
- ImGui (included in project).

### Steps
1. Clone this repo:
   ```sh
   git clone https://github.com/YOUR_USERNAME/CrosshairOverlay.git
