# Chess
- This is a chess engine created with JavaScript, HTML, and CSS. The computer can play against you with three difficulty levels: easy, medium, hard. The chess engine uses the minimax algorithm to decide on the best move to make. The minimax algorithm examines a large tree of possible moves that can be played by the computer and the opponent (human).

---

## How To Play
- **Step: 1** Select the difficulty level.
- **Step: 2** Select the Board Color.
- **Step: 3** And then select the Piece Colour (Black or White).

---

## Features 
- 3 different board themes.
- 3 different difficulty levels.
- Choice between Black and White Pieces.
- Restart and Draw buttons.

---

## Stats Button
The STATS button takes us to a different webpage where we can see the ranking of different players based on their scores in:
- Rapid
- Daily
- Daily 960
- Blitz
- Bullet
- King of the Hill
- Crazy House
- 3 Check
- Doubles
These results have been taken from **chess.com** using their API **"https://api.chess.com/pub/leaderboards"**.

  ---

## Demo
https://aryansjc001.github.io/Chess/

---

## Working of the Code
- This game is made by using Minimax Algorithm which helps the computer to differentiate between the move is better and will lead to more point and the one which may lead to alose.
- To do so first I assigned the different pieces on the board with their respective valid moves(in **Pieces.js**) and then applied the Minimax Algorithm(in **ComputerPlayer.js**).

  - Min: Represents the opponent trying to minimize your score.
  - Max: Represents your algorithm trying to maximize the score.
    
- The algorithm recursively evaluates all possible moves to a certain depth, assigns a score to each possible outcome, and chooses the move with the best score.
