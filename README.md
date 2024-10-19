# Phase Jumper

<p align="center">
  <img src="https://github.com/MicksS1/SideScroll-GameProg/assets/158981991/84f156fe-552a-47bd-acdc-a8668b1820b1">
</p>

## 🔴 About This Project
<p align="justify">This is one of my first projects in Unity, designed to help me grasp the fundamentals by building a side-scroller. Through this project, I’ve gained experience with Unity’s 2D physics system, implemented basic player movement, manipulated game objects, worked with tilemaps, and utilized JSON saving data, among other skills.</p>

<br>

## 📋 Project Info

<b> Developed with Unity 2022 </b>

| **Role** | **Name** | **Development Time** 
|:-|:-|:-|
| Game Programmer | Michael Ardisa | 1 week |

<details>
  <summary> <b>My Contribution (Game programmer)</b> </summary>
  
  - Core mechanics
  - UI Navigation
  - Bug Fixing
  - Level Design
  - Game Design
  
</details>

<br>

## ♦️About Game
<p align="justify">Phase Jumper is a fast paced side scroller where the main character has the ability to teleport through objects! Try your best to finish the levels as fast as possible with as little deaths as possible.  </p>

<br>

## 🎮 Gameplay
<p align="justify">This game is all about teleportation and parkour! Do your best to avoid traps to finish the level. There are currently 3 levels and I'm planning to add more in the future!  </p>

<br>

## ⚙️ Game Mechanics I Created
### Simple Saving System
<img src="https://github.com/user-attachments/assets/4bfda7b3-ab3c-4c10-80ee-f5b0a01c8f73" style="width: 67%;">

- Logic is located within the `SaveManager.cs` script
- JSON file format is used to store key player data.
- Data includes player's last level, checkpoint position, death count, and timer.
- All data is saved within the game to track player progress.

### Simple Checkpoint System
![CheckpointGameplay (1)](https://github.com/user-attachments/assets/c576c69e-fa9a-4c83-af7e-bfa9c3b02156)

- Logic is located within the `CP_Behaviour.cs` script
- The checkpoint system integrates with the saving system, triggering a save at each checkpoint.
- PlayerPrefs is used to store updated player X and Y coordinates.
- The coordinates are combined into a Vector2 and saved in JSON format for tracking progress.

<br>

## 📜 Scripts

|  Script       | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| `GameManager.cs` | Manages the game flow, main menu, pause menu, etc. |
| `AudioManager.cs`  | Responsible for all the audio in the game. |
| `PMove.cs`  | Manages all player movements. |
| `SaveManager.cs`  | Manages the logic behind saving the player's data. |
| `CP_Behaviour.cs`  | Manages the behaviour of checkpoints |
| `etc`  |

<br>

## 🕹️ Controls

| **Key Binding** | **Function** |
|:-|:-|
| A, S, D | Basic movement |
| Space | Jump |
| S-MidAir | Fast-Fall |
| Esc | Pause |
| L-Shift or J | Teleport |

<br>

## 💻 Setup

If you want to try the game out, go to the right of the list of files, click "Releases" or just click <a href="https://github.com/MichaelArdisa/PhaseJumper/releases/download/v1.0/PhaseJumper.zip">here</th>
