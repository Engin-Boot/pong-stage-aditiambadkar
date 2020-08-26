# start-Round-Computer-Player

## Feature

Indicates start of the new game or start of a new round
in an in-progress game

## Acceptance Criteria

### Scenario 1: Player completes game level selection

Given player selects the game level and player is on the game arena page

When player is at game arena page

Then player clicks on the pong ball with the paddle and ball goes towards
computer player and new game begins

### Scenario 2: Player misses pong ball and starts new round

Given player misses pong ball and player is on game arena page

When player is ready to start new round

Then player clicks on the pong ball with the paddle and ball goes towards
computer player and game round begins


### Scenario 3: Computer misses pong ball and starts new round

Given computer misses pong ball and player is on game arena page

When player is ready for new round

Then computer move generates and hits pong ball with the paddle and ball goes towards
player and game round begins
