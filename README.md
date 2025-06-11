## 🎮 2-Player Snake

### 📝 Description  
Two players control separate snakes. Try to survive longer or trap the other player.

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
