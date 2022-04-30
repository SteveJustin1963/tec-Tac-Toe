# Tic-Tac-Toe / Naughts and Crosses 
  
Now in MINT code...
- you vs the computer, c vs c
- computer can have best or next legal move or a mix of both
- 


```
>1 2 3
>4 5 6
>7 8 9

>2

>1 X 3
>4 O 6
>7 8 9

>1

>X X O
>4 O 6
>7 8 9
```

algorithm for playing tic tac toe:

1. start with an empty 3x3 grid
2. player 1 chooses a position on the grid by putting an 'X' in one of the empty cells
3. player 2 chooses a position on the grid by putting an 'O' in one of the empty cells
4. if either player has three of their symbols in a row horizontally, vertically, or diagonally, that player wins the game
5. if all the cells on the grid are filled and neither player has won, the game ends in a drawwrite me a program to do this

Here is pseudocode for the algorithm above:
```
// start with an empty 3x3 grid
grid = [['', '', ''], ['', '', ''], ['', '', '']];

// player 1 chooses a position on the grid
grid[0][0] = 'X';

// player 2 chooses a position on the grid
grid[1][1] = 'O';

// if player 1 has three 'X' symbols in a row, player 1 wins
if (grid[0][0] == 'X' && grid[0][1] == 'X' && grid[0][2] == 'X') {
  print('Player 1 wins!');
}

// if player 2 has three 'O' symbols in a row, player 2 wins
if (grid[1][0] == 'O' && grid[1][1] == 'O' && grid[1][2] == 'O') {
  print('Player 2 wins!');
}

// if all the cells on the grid are filled and neither player has won, the game ends in a draw
if (grid[0][0] != '' && grid[0][1] != '' && grid[0][2] != '' && 
    grid[1][0] != '' && grid[1][1] != '' && grid[1][2] != '' &&
    grid[2][0] != '' && grid[2][1] != '' && grid[2][2] != '') {
  print('The game ends in a draw.');
}
```

### Iterate
- dice
- chekers
- chess
- bridge
- go
- two up
- pokies 3 wheel
- lotto
- minesweeper
- nim
- 


### Ref
- https://en.wikipedia.org/wiki/Tic-tac-toe
- https://rosettacode.org/wiki/Tic-tac-toe
- 
