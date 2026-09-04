# 🐱 LanitoPet
 
A cute pixel art desktop companion that lives on your screen while you work, play, or browse.
 
 
## 📖 Overview
 
LanitoPet is a lightweight desktop pet application that runs alongside your other apps, providing a cute pixel art companion that walks, reacts, and keeps you company while you work.
 
Think of it as a Tamagotchi for your desktop — but without the feeding responsibilities! Just a friendly little sprite that roams around your screen.
 
## ✨ Features
 
- 🎮 **Interactive Pet** — Click, drag, and play with your desktop companion
- 💬 **Speech Bubbles** — Your pet reacts with random messages and emojis
- 🖥️ **Desktop Roaming** — Walks around your screen, bounces off edges
- 🤔 **"Wonder" Mode** — Randomly stops to "think" before changing direction
- 🎨 **Pixel Art Style** — Retro pixel aesthetic for that nostalgic feel
- ⚡ **Lightweight** — Runs quietly in the background without slowing down your PC
## 🎯 Current Status
 
**Version:** 1.0.0
**Status:** Active development
 
Currently includes:
 
- ✅ One fully animated sprite (credit: Bonzeet from DeviantArt)
- ✅ Walking, idle, and "wonder" animations
- ✅ Desktop roaming and edge detection
- ✅ Speech bubble interactions
- ✅ Draggable window
- ✅ Standalone Windows executable
## 🚀 Installation
 
### Windows
 
1. Download the latest release (link coming soon)
2. Extract the zip file
3. Run `LanitoPet.exe`
No installation required — just unzip and run!
 
## 🎮 Controls
 
| Action | Result |
|--------|--------|
| Click  | Pet reacts with a speech bubble |
| Drag   | Move the pet anywhere on your screen |
 
## 🛠️ Built With
 
- **Java 25** — Core application logic
- **JavaFX** — UI and rendering
- **Maven** — Dependency management
- **jlink + jpackage** — Standalone executable packaging
## 📦 Project Structure
 
```
LanitoPet/
├── src/
│   ├── main/
│   │   ├── java/com/lanitoman/petnet/
│   │   │   ├── App.java                    # Application entry point
│   │   │   ├── SimpleWindow.java           # Window management
│   │   │   ├── SimpleSpriteAnimation.java  # Sprite animation logic
│   │   │   └── SimpleBubbleText.java       # Speech bubble system
│   │   └── resources/
│   │       ├── images/                     # Sprite assets
│   │       └── fonts/                      # Pixel fonts
│   └── test/
└── pom.xml                                 # Maven configuration
```
 
## 🎨 Credits
 
- **Sprite Design** — Bonzeet (DeviantArt)
- **Development** — Lanitoman
## 🗺️ Roadmap
 
### Version 1.1 (Planned)
- [ ] Multiple character selection (cat, dog, fox, etc.)
- [ ] Character switcher in the UI
- [ ] Settings panel
### Version 1.2 (Planned)
- [ ] More animations (sleeping, eating, playing)
- [ ] Sound effects
- [ ] Taskbar integration
### Version 2.0 (Future)
- [ ] Cross-platform support (macOS, Linux)
- [ ] Custom sprite uploader
- [ ] Online character gallery
## 📝 License
 
**All Rights Reserved** — This project is currently not open source.
 
## 📬 Contact
 
**Developer:** Lanitoman
**Email:** lanitomanmd@gmail.com
 
---
 
<div align="center">
Made with ❤️ by Lanitoman
 
</div>
