# Chess-Style Work Timer

A simple yet powerful web-based timer inspired by the **chess clock mechanism**, designed to help you **track focused work time** accurately by switching between "Work" and "Break" modes. This tool was created to measure **exactly how much time you spend actively working**, minimizing guesswork and distractions.


![3](https://github.com/user-attachments/assets/24739414-e892-40c1-8aa8-9b081fc74d25)

---
## 🎯 Why I Created This

As a developer, I often found myself overestimating how long I worked on a project. Traditional timers don’t account for breaks, distractions, or interruptions — they just run.

So, I built this **dual-player timer** (like in chess) where:

- ✅ **Green Timer (`Player 1`)** = **Work Time**  
- ❌ **Red Timer (`Player 2`)** = **Break / Pause / Distraction Time**

### How It Works:
- Start the timer on **green (Player 1)** when you begin working.
- Every time you get distracted, pause, or take a break — **switch to red (Player 2)**.
- When you return to work — **switch back to green**.
- At the end of the session, you’ll see **exactly how much real time you spent working** vs. being idle.

This gives you **honest productivity insights** — no more guessing!

---

## 🔧 Features

- Dual timer display with color-coded indicators:
  - 💚 Green: Work mode
  - ❤️ Red: Break/distraction mode
- Smooth animations and sleek dark UI with glowing effects
- Responsive design with background video blur effect
- One-click controls: Switch, Pause, Reset
- Accurate time tracking down to the second (with hours support)
- Auto-initializes on load

---

## 🖥️ How to Use

1. Open the HTML file in any modern browser (no server needed).
2. The timer starts at `00:00:00` for both players.
3. Click **"Switch"** to start the **green (work) timer**.
4. While working, let the green timer run.
5. When you pause or get distracted:
   - Click **"Switch"** → red timer starts (break time)
6. When resuming work:
   - Click **"Switch"** again → green timer resumes
7. To pause entirely, click **"Pause"**
8. To restart from zero, click **"Reset"**

> ⏱️ Only the **green timer** counts as productive work time.

---

## 🛠️ How to Create Your Own Version

This is a standalone HTML file — no frameworks or dependencies required!

### Step-by-Step Setup

1. **Create an HTML file** (e.g., `work-timer.html`)
2. Copy the full code into it.
3. Add a video file (`2.mp4`) in the same directory, or:
   - Replace `src="./2.mp4"` with your own background video
   - Or remove the `<video>` tag if not needed
4. Open the file in your browser:  
   ```bash
   open work-timer.html
   ```
### Customize It
PART | What You Can Change
-----|------
✅ Colors | Modify `#player1` (green) and `#player2` (red) colors in CSS
🎨 UI | Adjust `background-color` , `box-shadow`, `border-radius` in `.timer-container`
📹 Background | Replace `2.mp4`or change filter effects (`blur`,`hue-rotate`, `brightness` )
🔊 Sound? | Remove `muted` if you want sound, or add audio cues via JS
🕹️ Behavior | Modify `switchPlayer()` , add beep on switch, export data, etc.

----------
### 💡 Pro Tips
- Use this during Pomodoro sessions: work (25 min), break (5 min) — but with real accountability.
- Track multiple projects by noting times manually or enhancing the app with localStorage.
- Combine with screen-time apps for deeper focus analytics.

### 📦 Requirements
- A modern browser (Chrome, Firefox, Edge, Safari)
- Optional: Background video (2.mp4) in the same folder
- No internet or build tools required!

### 🤝 Want to Improve It?
Feel free to add:
- LocalStorage to save sessions
- Export to CSV
- Sound alerts on switch
- Mobile touch optimization
- Dark/light mode toggle
Pull requests welcome!

---
### 📝 License
MIT — Use freely for personal or commercial projects.

---
🎯 Stay honest with your time. Work less, achieve more.
Made with ❤️ for focused creators.#   d u a l - t i m e r 
 
 #   d u a l - t i m e r 
 
 
