# increase-Score

## Feature

Increases the computer or player score

## Acceptance Criteria

### Scenario: Player misses the pong ball

Given computer hits the pong ball and pong ball simulator
moves it towards player with direction, speed and randomness

When pong ball goes beyond contact limit of front face of
player paddle

Then player misses pong ball computer score increases by 1

### Scenario: Computer misses pong ball

Given player hits the pong ball and pong ball simulator
moves it towards computer with direction, speed and randomness

When pong ball goes beyond contact limit of front face of
computer paddle

Then computer misses pong ball player score increases by 1
