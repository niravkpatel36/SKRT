# SKRT

A cross-platform Python application built with Kivy, featuring a perspective style runner game called SKRT. The project demonstrates modern UI development in Python and includes concepts such as layouts, widgets, canvas drawing, animation, procedural generation, and game state management.

SKRT challenges the player to navigate a spaceship along a track while the world scrolls forward. The game runs on desktop and can be packaged for mobile platforms.

<img width="674" height="321" alt="img1" src="https://github.com/user-attachments/assets/5a56a82d-4805-4d76-a563-83e56e4cd803" />

<img width="674" height="321" alt="img2" src="https://github.com/user-attachments/assets/e2a02baa-1c0f-4010-b172-55fb0d42707c" />

<img width="674" height="321" alt="img3" src="https://github.com/user-attachments/assets/7fa147a6-9ff4-43c2-b1b7-a295a5729132" />

## Features

- Cross-platform graphical application
- Responsive interface
- Smooth animation and movement
- Perspective visual effect
- Collision detection
- Game menu and score display
- Keyboard and touch friendly controls
- Modular code structure

## Gameplay Overview

Navigate the ship while staying on the path. The camera simulates depth using perspective projection. Tiles scroll forward to create an infinite world. The game tracks score and resets on collision.

| **System** | **Description**                                     |
|------------|-----------------------------------------------------|
| Rendering  | Perspective effect using geometry transforms        |
| Input      | Keyboard and touch supported                        |
| UI         | Menus, overlays, and score text                     |
| Audio      | Optional sound effects                              |
| State      | Running, paused, and game over logic                |
| World      | Random tile generation                              |

## Getting Started

### Install Kivy
```
pip install kivy
```

### Clone the repository
```
git clone https://github.com/niravkpatel36/SKRT.git
cd SKRT
```

### Run the app
```
python main.py
```

### Project Structure

```
SKRT/
├── README.md
├── .gitignore
│
├── main.py                 # Application entrypoint
├── menu.py                 # Menu logic and screens
├── transforms.py           # Game/UI transformations
├── user_actions.py         # Input handling and game controls
├── menu.kv                 # Kivy layout for menu
├── skrt.kv                 # Kivy layout for main game interface
│
├── audio/                  # Game audio assets
│   ├── begin.wav
│   ├── galaxy.wav
│   ├── gameover_impact.wav
│   ├── gameover_voice.wav
│   ├── music1.wav
│   └── restart.wav
│
├── fonts/                  # Custom fonts
│   ├── Eurostile.ttf
│   └── Sackers-Gothic-Std-Light.ttf
│
└── images/                 # Visual assets
```

## License
SKRT is licensed under the MIT License.