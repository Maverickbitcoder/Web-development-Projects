# 🧠 Neon Sudoku 3D – README

Welcome to **Neon Sudoku 3D**, an immersive and visually stunning Sudoku puzzle game built using only **HTML5**, **CSS3**, and **vanilla JavaScript**. This single-page web app features an animated 3D neon UI, interactive gameplay, real-time validation, and game logic all packed into one standalone `.html` file.

---

## 🎮 Features

### 🎲 Game Functionality

* 9x9 Sudoku grid with 3x3 subgrid highlighting.
* Automatically generated valid puzzles with varying difficulty levels.
* On-screen number pad for mobile and desktop input.
* Real-time answer checking and mistake highlighting.
* Show Solution button with graceful animations.
* Get Hint functionality reveals one correct cell.
* Timer, score tracking, error count, and difficulty display.
* Win detection with celebratory animations and confetti.

### 🎨 Visual and UX Design

* **Neon Glow** & **Glassmorphism** styling.
* Animated background with floating 3D shapes.
* Smooth CSS transitions, glowing effects, pulse & shake feedback.
* 3D-like interactions on hover.
* Fully **responsive** design.
* Accessible and mobile-friendly.

### 🛠️ Technical Details

* Single HTML file: Includes all HTML, CSS, and JavaScript.
* No external libraries or frameworks used.
* Self-contained Sudoku generator and validator (recursive backtracking).

---

## 📁 File Structure

```plaintext
sudoku.html        # Main (and only) file with all game code
```

---

## ⚙️ How It Works (Core Modules)

### HTML Components

* `.header` – Game title and subtitle
* `.game-controls` – Control buttons (New Game, Check Answer, etc.)
* `.stats-container` – Timer, errors, score, difficulty
* `.sudoku-grid` – 9x9 grid rendered dynamically
* `.number-pad` – Animated pad to select numbers
* `.win-overlay` – Endgame screen with stats and celebration

### CSS Highlights

* Defined in `<style>` within `:root` for theme customization
* Neon colors, gradients, hover shadows
* Animations:

  * `@keyframes glow`, `highlightPulse`, `errorShake`, `winPulse`
  * `float-around` for animated background shapes
* Responsive design via media queries

### JavaScript (Class: `NeonSudoku3D`)

#### Properties:

* `grid`, `solution`, `prefilled`: 2D arrays
* `selectedCell`, `timer`, `score`, `errors`, `difficulty`

#### Main Methods:

* `init()` – Sets up board and UI
* `generateSudoku()` – Generates board using `fillGrid()`
* `fillGrid(grid)` – Recursive Sudoku solver
* `createPuzzle()` – Removes numbers for difficulty
* `renderGrid()` – Builds and updates the visual board
* `selectCell()` – Handles cell click
* `selectNumber()` – Inputs a number via pad or keyboard
* `checkSolution()` – Compares input with actual solution
* `showSolution()` – Reveals all correct answers
* `getHint()` – Randomly fills one correct value
* `checkWin()` – Checks for game completion
* `showWinAnimation()` – Triggers celebration UI and confetti
* `startTimer()` and `stopTimer()` – Game timer logic

---

## 🚀 How to Use

### 1. 🧾 Open the Game

Simply open the `sudoku.html` file in any modern web browser (Chrome, Firefox, Edge).

### 2. 🧩 Play

* Click on empty cells to select them.
* Use number pad or keyboard to fill in values.
* Use buttons to:

  * Start new games
  * Check correctness
  * Reveal answers
  * Request hints

### 3. 🥳 Win

* Finish the puzzle correctly to see animated confetti and win screen.

---

## 🧪 Bash Deployment (Optional for Dev Use)

If you want to serve this locally on a development server:

```bash
# Simple Python HTTP server
python3 -m http.server 8080
# Visit http://localhost:8080/sudoku.html
```

---

## 📜 License

This project is open-source and free to use. Feel free to modify, share, and enhance it for learning or entertainment.

