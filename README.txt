Player Controls:

A-Moves the block right 1 unit
D-Moves the block left 1 unit
S-Moves the block down 1 unit
Spacebar-Changes Board (Board changes in the following order starting from center: Right,Center,Left,Center)
W-Rotates block (1 of 4 rotations going clockwise)
P-Pauses game
Enter/Return-Starts the game

Gameplay Changes:
-Penalty blocks and misplaced color blocks are removed by creating a line of the same color (e.g. a red block on green board can be removed by completing a red line)
-Boards with more penalty blocks have higher priority when removing said blocks(e.g. if blue board has 3 red penalty blocks and green board has 1, then a penalty block is removed from blue board when a red line is completed)
-If the game detects a collision when the player changes boards it will not allow movement to that board and will choose another

Possible bugs/glitches:
-When changing boards collision may fail and merge the player block with an existing one in the same spot
-(Rare) collision detection failure when player holds down A, D, or S

Comments:
(Personal) I had no prior knowledge of SDL and only had basics of C++ at the time I recieved this test
thanks for including the tutorial it helped out alot. I learned many new things with this test and will continue to add more to it.