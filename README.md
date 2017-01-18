# Assignment 28

For this assignment you will be using a 2-dimensional array to create a tic-tac-toe board (3 x 3).

## First Step

Use a 2D array to create your board. Then, display the board. Each "empty" space should show a number 1-9 that corresponds to the space.
The board should also have the "look" of a tic-tac-toe board. Look below for an example.

Once you can display a grid, make it possible to place pieces (X's and O's).

Note: your final program will have to use two classes (runner + one other class). For day one I am not requiring that you start with two classes,
but it would probably be a good idea to at least think about the methods you would be using in your class.

## Second Step

Make sure your structure your program into two classes and paste in your code from step 1, if you haven't already. Think about what class variables you will need, what needs to
be done in the constructor, and what methods you need.

Remember that the only code inside the Runner should be for getting player names, creating the Board object, and calling methods. All game logic should be in your Board class.

## Third Step

Fill in your methods in your class. Make sure everything works (turns alternate, it doesn't let players move in an occupied space or non-existent space, stops the game when someone wins).

### Helpful Conversions

Convert int to String: Integer.toString(num)

Convert int to char: Character.forDigit(num, 10)

### Sample Outputs

```
Tic-Tac-Toe!

Enter name of player 1: Joe
Enter name of player 2: Jose

1    |    2    |    3    
------------------------
4    |    5    |    6    
------------------------
7    |    8    |    9    

Joe's turn: 5

1    |    2    |    3    
------------------------
4    |    X    |    6    
------------------------
7    |    8    |    9    

Jose's turn: 1

O    |    2    |    3    
------------------------
4    |    X    |    6    
------------------------
7    |    8    |    9    

Joe's turn: 2

O    |    X    |    3    
------------------------
4    |    X    |    6    
------------------------
7    |    8    |    9    

Jose's turn: 8

O    |    X    |    3    
------------------------
4    |    X    |    6    
------------------------
7    |    O    |    9    

Joe's turn: 4

O    |    X    |    3    
------------------------
X    |    X    |    6    
------------------------
7    |    O    |    9    

Jose's turn: 7

O    |    X    |    3    
------------------------
X    |    X    |    6    
------------------------
O    |    O    |    9    

Joe's turn: 6

O    |    X    |    3    
------------------------
X    |    X    |    X    
------------------------
O    |    O    |    9  

Joe wins!
```

