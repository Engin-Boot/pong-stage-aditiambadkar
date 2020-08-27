# computer-Move-Generator

## Feature

Generates computer move for computer-player game mode

## Acceptance Criteria

### Scenario 1: Player plays move by hitting pong ball with paddle

Given player plays move and pong ball simulator moves ball towards
computer with direction, speed and randomness

When pong ball approaches the computer

Then computer move generator generates computer move by hitting the
pong ball with paddle with some percentage precision

### Scenario 3: Computer misses pong ball and starts new round

Given computer misses pong ball and player is on game arena page

When computer misses pong ball

Then computer move generates and hits pong ball with the paddle and
pong ball simulator moves ball towards computer with direction, speed
and randomness
