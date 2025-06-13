<p align="center">
<img src="https://github.com/user-attachments/assets/95889be7-0c89-4798-ad38-9bd552a4670d" width="300">
</p>

<h1 align="center"> 
Double Snake
</h1>

<p align="center">
Two players control separate snakes. Try to survive longer or trap the other player.
</p>

---
## 🎮 Gameplay Showcase

Here’s a quick look at the game in action:
<p align="center">
<img src="https://github.com/user-attachments/assets/47317393-facc-4c31-98fb-25226d7a7a63" width="500">
</p>

---

### 🕹️ Controls

| Button   | Action         |
|----------|----------------|
| A_UP     | P1 Move up     |
| A_DOWN   | P1 Move down   |
| A_LEFT   | P1 Move left   |
| A_RIGHT  | P1 Move right  |
| B_UP     | P2 Move up     |
| B_DOWN   | P2 Move down   |
| B_LEFT   | P2 Move left   |
| B_RIGHT  | P2 Move right  |
| EXIT     | Exit game      |

---

### 🧠 Logic Overview  
Each snake has independent movement and can collide with itself, the opponent, or the borders.

---

### 🧩 Game Loop Structure  
1. Read both inputs  
2. Move snakes  
3. Check collisions  
4. Render  
5. Delay  

---

### ❌ End Conditions  
- Either snake crashes  
- Exit input is received  

---

### 🧪 Notes & Improvements  
- Add head-to-head logic  
- Track per-player score  
