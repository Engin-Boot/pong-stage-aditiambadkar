# Interaction Sequences

## Startup Sequence

1. Player clicks on "Pong Game Application" icon on the computer screen and launches
the game.
2. On launching Pong Game, display-Main-Menu displays the main menu which has 2 options
"New Player" and "Existing Player".
3. If the player clicks on "New Player" option from the main menu, create-New-Player
displays a pop up text box and player types his or her name.
If the player clicks on "Existing Player" option from the main menu
and no existing players are available, display-Existing-Players displays
"No Existing Players" message and prompts player to go back to main menu.
If the player clicks on "Existing Player" option from the main menu
and one or more existing players are available, display-Existing-Players displays
icons of all existing players and player clicks one of them.
4. After player selection the display-Player-Menu displays "Store", "Start Game"
"Profile Details" and "Player Items" options. Player clicks on "Start Game" option
start-New-Game-Computer-Player initiates new game.
5. The get-Game-Level displays 3 game level options "Easy", "Medium" and "Hard".
If the player clicks on "Easy" option, the pong ball direction randomness
is set to 50% which increases by 10% after subsequent player point and pong ball
speed is set to 1 which increases by 1 after subsequent player point.
If the player clicks on "Medium" option, the pong ball direction randomness
is set to 70% which increases by 15% after subsequent player point and pong ball
speed is set to 2 which increases by 2 after subsequent player point.
If the player clicks on "Hard" option, the pong ball direction randomness
is set to 90% which increases by 10% after subsequent player point and pong ball
speed is set to 3 which increases by 3 after subsequent player point.

## Movement Initiation

1. Player completes game level selection and start-Round-Computer-Player
indicates start of new game. Player clicks on the pong ball with the paddle
and pong-Ball-Simulator moves the ball goes towards computer with direction,
speed and randomness and new game begins.
2. If computer misses pong ball, the computer-Move-Generator generates the
computer move hits pong ball with the paddle and pong-Ball-Simulator moves
the ball towards player and new round of game begins.
3. If player misses pong ball, player clicks on the pong ball with the
paddle and pong-Ball-Simulator moves the ball towards computer player and
new round of game begins.

## One score

1. If player hits the pong ball with paddle and pong ball simulator moves
the ball towards computer with direction, speed and randomness and ball
and paddles have X Y coordinates. If X Y coordinates of pong ball go
beyond contact limit of computer paddle front face pong-Ball-Miss-Checker
identifies it and computer misses pong ball and increase-Score
increases player points. The check-Score checks if player score is equal
to 11. If yes, then declare-Winner declares player as winner and game
ends. If no, computer-Move-Generator generates next computer move.
2. If computer hits the pong ball with paddle through
computer-Move-Generator move and pong ball simulator moves the ball
towards player with direction, speed and randomness and ball and paddles
have X Y coordinates. If X Y coordinates of pong ball go beyond contact
limit of player paddle front face pong-Ball-Miss-Checker identifies it
and computer misses pong ball and increase-Score increases player points.
The check-Score checks if computer score is equal to 11. If yes, then
declare-Winner declares computer as winner and game ends. If no,
player plays next move.

## Player wins

1. Player scores 11 before computer and declare-Winner declares player
as winner and add-Coins adds 50 game coins to player account.
2. The lucky-Draw-Cards displays 3 cards which mention random coin amounts
(10, 20, 50, 100, 500, 1000) out of these. The amounts are not visible to
player until selection of single card.
3. Player clicks on 1 of the 3 cards and the corresponding card discloses.
4. The add-Coins adds corresponding game coins to player account.
