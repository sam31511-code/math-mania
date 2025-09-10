# Times Table Bubble Pop 🎈✖️

A browser-based math practice game where bubbles float across the screen carrying multiplication problems.  
Your goal is to type the correct product before a bubble hits the **red barrier** on the left.

---

## 🎮 How to Play
1. **Open the game**  
   Double-click `times-table-bubble-pop.html` to launch it in your browser.

2. **Start the game**  
   - Click **Start** on the overlay to begin.
   - New bubbles will begin spawning from the right.

3. **Pop bubbles**  
   - Type the correct answer into the input box.  
   - Press **Enter** or click **Pop**.  
   - If correct, the matching bubble will pop and you’ll earn points.

4. **Watch the barrier**  
   - If a bubble reaches the red line (25% from the left), it gets stuck and adds to the **pile**.  
   - Too many piled bubbles = game over.

5. **Clear the pile (optional)**  
   - Click the **Clear Pile** button.  
   - This removes all piled bubbles but costs you **1 life**.

6. **Lives**  
   - You start with 3 lives.  
   - Lose all lives and it’s game over.

---

## ⚙️ Controls & Buttons
- **Start / Restart**: Begin a new game.
- **Pause**: Freeze the game temporarily.
- **Clear Pile**: Remove all piled bubbles (costs 1 life).
- **Answer Box**: Type your answer and press Enter or click Pop.

---

## 🛠️ Customization
On the start overlay you can tweak:
- **Spawn Rate (ms):** How often bubbles appear.  
  - Default = `2500` ms (1 new bubble every 2.5 seconds).
- **Speed (px/sec):** How fast bubbles travel left.  
  - Default = `60` px per second.

Change these to make the game easier or harder.

---

## 📂 Project Structure
- `times-table-bubble-pop.html`  
  - Contains **HTML** (page structure),  
  - **CSS** (styling),  
  - **JavaScript** (game logic).

Everything is bundled into a single file. No extra assets required.

---

## 💡 Key Features
- Covers **times tables 1×1 through 12×12**.
- Bubbles pop with an animation.
- Pile-up mechanic adds pressure and strategy.
- Customizable spawn rate and speed.
- Works offline in any modern browser (Chrome, Edge, Firefox, Safari).

---

## 🚀 Deployment
To put this on the web:
1. Host the HTML file on any static hosting (Netlify, GitHub Pages, etc.).
2. Share the link or embed it in another site with an `<iframe>`.

---

## 📜 License
You are free to use, modify, and share this game for personal or educational purposes.
