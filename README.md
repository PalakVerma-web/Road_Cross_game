# 🐢 Turtle Road Crossing Game

A simple arcade-style road crossing game built using Python's **turtle graphics** module. The objective is to help the player safely cross the road while avoiding incoming cars. Each successful crossing increases the difficulty.

---

## 🎮 Gameplay

* Control the player (turtle) using the **Up Arrow key**.
* Avoid colliding with moving cars.
* Each successful crossing:

  * Resets the player to the starting position
  * Increases the game level
  * Speeds up the cars

---

## 🧱 Project Structure

```
├── main.py              # Main game loop
├── player.py            # Player (turtle) behavior
├── car_manager.py       # Car creation and movement logic
├── scoreboard.py        # Score and level tracking
└── README.md            # Project documentation
```

---

## ⚙️ Requirements

* Python 3.x
* Built-in modules:

  * `turtle`
  * `time`

No external dependencies required.

---

## ▶️ How to Run

1. Clone the repository:

   ```
   git clone https://github.com/your-username/turtle-road-crossing.git
   ```

2. Navigate into the project folder:

   ```
   cd turtle-road-crossing
   ```

3. Run the game:

   ```
   python main.py
   ```

---

## 🕹️ Controls

| Key        | Action       |
| ---------- | ------------ |
| ↑ (Up Key) | Move forward |

---

## 🚧 Game Logic Overview

* **Player Movement**: Controlled via keyboard input.
* **Car Manager**:

  * Spawns cars at random intervals
  * Moves them across the screen
  * Increases speed as levels progress
* **Collision Detection**:

  * Game ends if player collides with a car
* **Level Progression**:

  * Triggered when player reaches the finish line

---

## 💡 Future Improvements

* Add sound effects and background music
* Introduce multiple lanes and varied traffic speeds
* Add lives instead of instant game over
* Implement a start/restart menu



