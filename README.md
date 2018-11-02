# 7g
7g 
/// Print the board
7 val printBoard : b: board -> unit
DONE!


8
9 /// Check whether a pit is the player 's home
10 val isHome : b: board -> p: player -> i:pit -> bool
?Thea

11
12 /// Check whether the game is over
13 val isGameOver : b: board -> bool
Semi-Done (Output som int i stedet for bool er committed

15 /// Get the pit of next move from the user
16 val getMove : b: board -> p: player -> q: string -> pit
? Maria

18 /// Distributing beans counter clockwise ,
19 /// capturing when relevant
20 val distribute :
21 b: board -> p: player -> i: pit -> board * player * pit
? Mikkel

23 /// Interact with the user through getMove to perform
24 /// a possibly repeated turn of a player
25 val turn : b: board -> p: player -> board
26
27 /// Play game until one side is empty
28 val play : b: board -> p: player -> board
