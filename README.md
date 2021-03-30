# A Classic TicTacToe game using Java Swing.
***
## The user is initially displayed with an option to choose your opponent, either against the computer or a friend.
 
![Capture_ticTacToe_MainMenu](https://github.com/04xRaynal/TicTacToe_JavaSwing/blob/705a2651beee45cd8908febde91c4d6e9598b456/Captured%20Images/Capture_TicTacToe_MainMenu.PNG)

---
Play alternates between the user(player1) who initially is X and the player2/CPU which is O.

Image displaying a game between the user and CPU:

![Capture_TicTacToe_vsComputer](https://github.com/04xRaynal/TicTacToe_JavaSwing/blob/705a2651beee45cd8908febde91c4d6e9598b456/Captured%20Images/Capture_TicTacToe_vsComputer.PNG)

---
After the game ends a dialog box is displayed announcing the result and the score. The user is given an option for a re-match(play again).

![Capture_TicTacToe_vsComputerMessage](https://github.com/04xRaynal/TicTacToe_JavaSwing/blob/705a2651beee45cd8908febde91c4d6e9598b456/Captured%20Images/Capture_TicTacToe_vsComputerMessage.PNG)

---
If the user selects 'Yes' on the Play again option, a new game starts, but now the user (player 1) is O and the cpu/player2 is X.
The mark ('X' and 'O') alternates every new game. X always plays first.

![Capture_TicTacToe_vsComputer_2](https://github.com/04xRaynal/TicTacToe_JavaSwing/blob/705a2651beee45cd8908febde91c4d6e9598b456/Captured%20Images/Capture_TicTacToe_vsComputer_2.PNG)

![Capture_TicTacToe_vsComputerMessage_2](https://github.com/04xRaynal/TicTacToe_JavaSwing/blob/705a2651beee45cd8908febde91c4d6e9598b456/Captured%20Images/Capture_TicTacToe_vsComputerMessage_2.PNG)

***
When the option of playing against the computer is selected, the program automatically plays its turn. 
Initially the user is X and CPU is O.

The computer's strategy is first to complete 3 O's in a row, or if that is not possible, to block a row of 3 X's, or if that is not possible, to move randomly.
***

Image displaying a game between Player 1 & Player 2 (vs Friend):

![Capture_TicTacToe_vsFriend](https://github.com/04xRaynal/TicTacToe_JavaSwing/blob/705a2651beee45cd8908febde91c4d6e9598b456/Captured%20Images/Capture_TicTacToe_vsFriend.PNG)

![Capture_TicTacToe_vsFriendMessage](https://github.com/04xRaynal/TicTacToe_JavaSwing/blob/705a2651beee45cd8908febde91c4d6e9598b456/Captured%20Images/Capture_TicTacToe_vsFriendMessage.PNG)

---

The score between the two players is also recorded and displayed at the bottom, it updates after every game.

After the end of a game, if the user selects 'No' on the Play again option, the frame resets to the main menu of options and all the scores are reseted.

Top panel displays labels which indicate the turn of each player and their corresponding mark (either X or O).
 