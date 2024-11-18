# Game 2048🎮

## Explore the Demo
- [DEMO LINK](https://rdudchar.github.io/Game-2048/)

## Sample game 2048
 - [**Game-2048**](https://play2048.co/)

## **Description**
2048 is a game that will help you unwind and pass the time in an interesting way. A real challenge for your mind. The objective is to combine tiles with the same numbers to create a tile with the highest possible value — 2048. With every move, a new tile is added to the board, and only your decisions will determine whether the game continues or leads to a dead-end (failure).

The game works quite simply: every time two matching tiles touch, they merge and double in value. But it’s not that easy — tiles can only move in one of four directions, and you must constantly think about how to make room for new tiles while avoiding situations where the board is full and no moves are left.

The game is made more difficult by the 4 tile that appears only in 10% of cases. Every move matters, because not only your progress, but also your current score depends on how many tiles you manage to combine in one move.

It’s a game about planning and achieving the highest possible score, with the ultimate goal of creating the 2048 tile.

## <h2>Technologies Used</h2>
[![My Skills](https://skillicons.dev/icons?i=js,html,css,scss)](https://skillicons.dev)

## <h2>Features of the 2048 Game</h2>

**1.Game Initialization & Restart**
Ability to start a new game (start) and restart the game (restart).

**2.Tile Movement**
Movement of tiles in four directions: Left (moveLeft), Right (moveRight), Up (moveUp), and Down (moveDown).

**3.Tile Generation**
Random generation of new tiles in empty cells after every move.
90% chance of generating a tile with a value of 2 and a 10% chance for a tile with a value of 4.

**4.State Validation**
isStateValid: Checks if any valid moves are still possible.
isDefeat: Determines if the game is over by checking for no more possible moves.
isVictory: Checks if a tile with a value of 2048 exists on the board, indicating a win.

**5.Matrix Rotation**
Implements rotation methods (rotateLeft and rotateRight) to handle "Up" and "Down" movements by changing the orientation of the board, applying the same algorithm for tile shifting in all directions.

**6.Score Tracking**
Keeps track of the score based on the tiles merged during each move.

**7.Game Status Management**
Updates and displays the current game status: Idle, Playing, Win, or Lose.

**8.Responsive User Interface**
Dynamically updates the game board and game status on the screen, providing real-time feedback.

**9.Message Notifications**
Displays win and game-over messages based on the state of the game.

## <h2>Get the initial code</h2>
1. Clone the repository:
   - git clone in your PC https://github.com/rdudchar/Game-2048;
   - code (name project).
2. Run npm install to install the dependencies
3. Create a branch for you solution (e.g. git switch -c develop)
4. Run npm start to run a development server at http://localhost:3000

---

**Usage:**
Go to the DEMO LINK to view the live version of the app.
