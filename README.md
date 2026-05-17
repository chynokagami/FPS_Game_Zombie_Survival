<div align="right">
  <a href="README_zh.md">简体中文</a> | <strong>English</strong> | <a href="README_ja.md">日本語</a>
</div>

# 🧟 Zombie Time Attack FPS

A First-Person Shooter (FPS) game developed using **Unreal Engine 5.4.4**. Players must utilize their weapons to fend off relentless zombie attacks and eliminate as many enemies as possible before the unforgiving countdown reaches zero.

This project is built using **100% Blueprints** with no C++ code involved, making it an excellent reference or template for learning UE5 Blueprint logic and rapid prototyping.

---

## ✨ Core Features

*   **Pure Blueprint Architecture:** Zero coding barrier. All character controllers, game modes, UI logic, and AI behaviors are driven purely by UE5 Blueprints.
*   **Time Attack Mode:** Intense, time-limited gameplay. A real-time countdown is displayed on the screen, and the game concludes when the timer hits zero.
*   **Solid FPS Mechanics:**
    *   🎯 **Aim Down Sights (ADS):** Smooth transition to iron sights using the right mouse button.
    *   🔄 **Ammo Management:** Features ammo consumption upon firing and a tactical reload system triggered by the R key.
    *   🏃 **Tactical Movement (Sprinting):** Hold Shift to sprint, complete with seamless state transitions while running.
*   **Satisfying Combat Feedback:**
    *   💥 **Hit Knockback:** Bullets trigger realistic physical or animation-based knockback effects on zombies, significantly enhancing the shooting feel.

---

## 🎮 Controls

| Key | Action |
| :--- | :--- |
| **W, A, S, D** | Move |
| **Mouse** | Look / Aim |
| **Left Mouse Button (LMB)** | Fire |
| **Right Mouse Button (RMB)** | Aim Down Sights (ADS) |
| **R** | Reload |
| **Left Shift** | Sprint |
| **Esc** | Pause / Exit Game |

---

## 🛠️ How to Run

1. Ensure you have **Unreal Engine 5.4.4** installed on your system.
2. Clone or download this repository and extract the files to your local machine.
3. Double-click the `.uproject` file in the root directory to open the project in the UE5 Editor.
4. Locate the main level in the Content Browser, and click the **Play** button in the top toolbar to start the game.

---

## 📁 Project Structure

*(Note: Folder names can be adjusted based on your actual structure)*
*   `Content/Blueprints/` - Contains core logic including the player character, zombie AI, weapons, and game mode controllers.
*   `Content/Animations/` - Contains character and zombie Montages, Animation Blueprints (AnimBP), and related assets.
*   `Content/UI/` - Contains User Interface widgets (UMG) such as crosshairs, ammo counters, and the countdown timer.
*   `Content/Maps/` - Contains the game levels/maps.

---
**Engine Version:** Unreal Engine 5.4.4  
**Developer:** CHEN HAOYU (Martin Chen)
