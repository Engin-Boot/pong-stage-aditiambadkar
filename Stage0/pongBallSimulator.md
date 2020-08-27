# pong-Ball-Simulator

## Feature

Simulates the pong ball with speed, direction and randomness
in the game

## Acceptance Criteria

### Scenario 1: New game begins, player always starts first move

Given player completes player and game level selection
starts a new game

When player is on game arena page

Then player clicks on the pong ball with the paddle and pong ball
simulator moves the ball goes towards computer with direction,
speed and randomness and new game begins

### Scenario 2: Player misses pong ball and starts new round

Given player misses pong ball and player is on game arena page

When player is ready to start new round

Then player clicks on the pong ball with the paddle and pong ball
simulator moves the ball goes towards computer with direction,
speed and randomness and new round begins

### Scenario 3: Computer misses pong ball and starts new round

Given computer misses pong ball and player is on game arena page

When player is ready for new round

Then computer move generates and hits pong ball with the paddle and pong ball
simulator moves the ball goes towards the player with direction, speed and
randomness and new round begins
