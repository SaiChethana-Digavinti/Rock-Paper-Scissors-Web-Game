# Rock Paper Scissors Web Game

A simple and interactive **Rock Paper Scissors** web game built using **HTML, CSS, and JavaScript**. The game allows the player to compete against a computer-generated move, track the score, and save the score using browser local storage.

---

##  **Project Overview**

This project is a browser-based implementation of the classic **Rock Paper Scissors** game.

The player can choose:

- ✊ Rock
- ✋ Paper
- ✌️ Scissors

The computer randomly selects one of the three moves, and JavaScript determines whether the player wins, loses, or gets a tie.

---

## **Features**

-  Play Rock Paper Scissors against the computer
-  Random computer move generation
-  Win, loss, and tie score tracking
-  Score persistence using `localStorage`
-  Reset Score option
-  Auto Play mode
-  Keyboard controls
-  Simple dark-themed interface
-  Rock, Paper, and Scissors image icons

---

##  **Technologies Used**

- **HTML5** – Structure of the web page
- **CSS3** – Styling and layout
- **JavaScript** – Game logic and interaction
- **LocalStorage** – Saving the game score in the browser

---

##  **Project Structure**

```text
Rock-Paper-Scissors-Web-Game/
│
├── index.html
├── style.css
├── script.js
│
├── images/
│   ├── rock-emoji.png
│   ├── paper-emoji.png
│   └── scissors-emoji.png
│
└── README.md
```

---

##  **How the Game Works**

### 1️. **Player Move**

The player selects Rock, Paper, or Scissors.

### 2️. **Computer Move**

JavaScript uses `Math.random()` to randomly select the computer's move.

### 3️. **Result Calculation**

The game compares the two moves and displays the result.

| Player | Computer | Result |
|---|---|---|
| Rock | Scissors |  You Win |
| Rock | Paper |  You Lose |
| Rock | Rock |  Tie |
| Paper | Rock |  You Win |
| Paper | Scissors |  You Lose |
| Paper | Paper | Tie |
| Scissors | Paper |  You Win |
| Scissors | Rock |  You Lose |
| Scissors | Scissors |  Tie |

---

##  **Score Tracking**

The game maintains three scores:

```text
Wins
Losses
Ties
```

The score is saved using browser `localStorage`, so it can remain available after refreshing the page.

---

##  **Auto Play**

The **Auto Play** feature automatically plays rounds at one-second intervals.

- Click **Auto Play** to start.
- Click it again to stop.

---

##  **Keyboard Controls**

You can also play using the keyboard:

| Key | Move |
|---|---|
| `R` | ✊ Rock |
| `P` | ✋ Paper |
| `S` | ✌️ Scissors |

---

##  **Reset Score**

The **Reset Score** button resets:

```text
Wins = 0
Losses = 0
Ties = 0
```

It also removes the saved score from `localStorage`.

---

##  **How to Run the Project**

### **Option 1 — Open Directly**

1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The game will open in your browser.

### **Option 2 — Using VS Code**

1. Open the project folder in **Visual Studio Code**.
2. Open `index.html`.
3. Run the project using **Live Server**.
4. Start playing! 🎮

---

##  **Author**

Sai Chethana Digavinti
