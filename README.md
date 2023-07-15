# Tic Tac 2.0
## setup:
This project requires the pygame module to run, so install pygame with:
`pip install pygame`
Then, after cloning this repo, run Tic_tac_2_online.py
## How to play:
### Description of the game:
This is basically a game of tic tac toe, but the players can now also add rows and columns in their turn instead of a circle or cross. If both the players add a row or column consecutively, the number of circles or crosses in a line required to win increases by one. This, however, can only happen once, and the next time rows or columns are added consecutively, it won't increase. If all the squares get filled and it's a draw, a row or column will be added on each side, and the game will continue. In this case as well, the number of circles or crosses in a line required to win increases by one. So, the game won't end until someone wins.
### offline mode:
When you run the game, it first asks you whether you want to play offline or online. If you select offline, it takes you to the menu screen, from which you can play the game. When playing, the color of the border indicates who's turn it is(red for X, blue for O). Depending on who won, player-1 or player-2's score will increase.
### online mode:
Please note that the online mode works only if both the computers are connected over the same local network. For me, it only works when both the computers are connected to my mobile's hotspot.
When you select the option to play online, you can then select whether you want to create a game, or join a game someone else has created. If you select *create*, It gives shows you your local ip address, and the other person you're playing with has to enter this in. If you select *Join*, It'll ask you to enter the IPv4 address of the host. After this is done, if the connection was successful, it takes you to the menu, and you can play the game as usual.
