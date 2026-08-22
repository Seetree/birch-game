# Game Design Document (v1.0)

## 1. Overview & Core Loop
* **Core Loop:** Player spawns into map and looks for hidden items
* **Win Condition:** All items are found
* **Loss Condition:** Time runs out

## 2. Controls & Platform Target
* **Target Platform:** PC (Windows)
* **Input Bindings:**
  * `WASD` / Arrow Keys: Player Movement
  * `Spacebar`: Action / Jump
  * `Esc`: Pause Menu

## 3. Cloud Leaderboard Spec
* **Trigger Events:** Submitted automatically upon game over or level completion.
* **API Payload Structure:**
  ```json
  {
    "player_id": "string",
    "score": 0,
    "completion_time_seconds": 0.0,
    "timestamp": "ISO-8601 string"
  }

## 4. Out of scope
* **Local multiplayer / co-op**
* **Mobile touch controls**
* **Character customization**
