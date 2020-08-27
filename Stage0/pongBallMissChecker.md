# pong-Ball-Miss-Checker

## Feature

Checks if the pong ball is missed by the player or computer

## Acceptance Criteria

### Scenario 1: Player plays move and computer misses pong ball

Given player hits the pong ball with paddle and pong ball
simulator moves the ball towards computer with direction, speed
and randomness and ball and paddles have X Y coordinates

When X Y coordinates of pong ball go beyond contact limit of computer
paddle front face

Then computer misses pong ball and increase player points

### Scenario 2: Computer plays move and player misses pong ball

Given computer hits the pong ball with paddle and pong ball
simulator moves the ball towards player with direction, speed
and randomness and ball and paddles have X Y coordinates

When X Y coordinates of pong ball go beyond contact limit of player
paddle front face

Then player misses pong ball and increase computer points
