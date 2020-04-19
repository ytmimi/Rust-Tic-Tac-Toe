# Rust Tic Tac Toe

I thought a good first beginner project would be writing a tic tac toe game in rust. I'm sure there is plenty of room for improvement, but the game plays and that's what matters.

## Building The Game

Clone the repository and build the project using ``$: cargo build --release``

To play the game run the binary created in ``target/release``. I'm on a windows machine and I run the game from the root director using ``$: target\release\tic-tac-toe.exe``


## Playing the Game

When the game stars the board will be displayed and Player1 will be prompted to pick an empty square.

```bash
   |   |
-----------
   |   |
-----------
   |   |
Player1 Pick an empty space on the board:

```

The player can select cells using the following integers:

      0  |  1  |  2
    ----------------
      3  |  4  |  5
    ----------------
      6  |  7  |  8

For example, if Player1 chooses 4 an ``X`` will appear on the board and Player2 will be prompted for their move

```bash
   |   |
-----------
   |   |
-----------
   |   |
Player1 Pick an empty space on the board:
4
You chose cell 4
   |   |
-----------
   | X |
-----------
   |   |
Player2 Pick an empty space on the board:
```

The game continues until some wins or the game is drawn.
